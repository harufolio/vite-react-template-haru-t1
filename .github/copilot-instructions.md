컴포넌트 선언 방식{
✅ export default function ComponentName({...}: Props) { ... }

❌ const ComponentName: React.FC<Props> = (...) => { ... }

❌ const ComponentName = (props: Props) => { ... }

}
