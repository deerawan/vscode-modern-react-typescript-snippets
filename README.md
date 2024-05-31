# Modern React Typescript Snippets

This extension provides you with a variety of shortcuts to make writing modern React components faster and easier using Typescript.

## Features

- Modern React with Typescript. No class. No PropTypes.
- Component snippets auto populate the component name based on filename which can be kebab-case or PascalCase
- Component snippets support TS interface and type
- Component snippets support functional declaration and arrow function
- useState hook snippet auto populates the setter name

## Snippets

| Snippet  | Renders                                |
| -------- | -------------------------------------- | --- |
| `rcf`    | Component using functional declaration |
| `rcf-d`  | ^ with default export                  |
| `rcf-p`  | ^ with props                           |
| `rcf-dp` | ^ with default export and props        |
| `rca`    | Component using arrow function         |
| `rca-d`  | ^ with default export                  |
| `rca-p`  | ^ with props                           |
| `rca-dp` | ^ with default export and props        |
| `rucb`   | useCallback Hook                       |
| `ruct`   | useContext Hook                        |
| `rudb`   | useDebugValue Hook                     |
| `rudf`   | useDeferredValue Hook                  |
| `rue`    | useEffect Hook                         |
| `rue-r`  | useEffect Hook with return             |
| `rui`    | useImperativeHandle Hook               |
| `rul`    | useLayoutEffect Hook                   |
| `rum`    | useMemo Hook                           |     
| `rurd`   | useReducer Hook                        |
| `rurf`   | useRef Hook                            |
| `rust`   | useState Hook                          |
| `rusy`   | useSyncExternalStore Hook              |
| `rut`    | useTransition Hook                     |

## Snippets Expansions

### Component using functional declaration

#### `rcf` - basic

```typescriptreact
export function |() {
  |
  return |
}
```

#### `rcf-d` - with default export

```typescriptreact
export default function |() {
  |
  return |
}
```

#### `rcf-p` - with props

```typescriptreact
export interface |Props {
  |:|
}

export function |({ | }: |Props) {
  |
  return |
}
```

#### `rcf-dp` - with default export and props

```typescriptreact
export interface |Props {
  |:|
}

export default function |({ | }: |Props) {
  |
  return |
}
```

### Component using arrow function

#### `rca` - basic

```typescriptreact
export const | = () => {
  |
  return |
}
```

#### `rca-d` - with default export

```typescriptreact
const | = () => {
  |
  return |
}

export default |;
```

#### `rca-p` - with props

```typescriptreact
export interface |Props {
  |:|
}

export const | = ({ | }: |Props) => {
  |
  return |
}
```

#### `rca-dp` - with default export and props

```typescriptreact
export interface |Props {
  |:|
}

const | = ({ | }: |Props) => {
  |
  return |
}

export default |;
```

### Hooks

#### `rucb` - useCallback Hook

```typescriptreact
const | = useCallback((|) => {
  |
}, [|])
```

#### `ruct` - useContext Hook

```typescriptreact
const | = useContext|(|)
```

#### `rudb` - useDebugValue Hook

```typescriptreact
useDebugValue|(|)
```

#### `rudf` - useDeferredValue Hook

```typescriptreact
const | = useDeferredValue|(|)
```

#### `rue` - useEffect Hook

```typescriptreact
useEffect(() => {
  |
}, [|])
```

#### `rue-r` - useEffect Hook with return

```typescriptreact
useEffect(() => {
  |
  return () => {
    |
  }
}, [|])
```

#### `rui` - useImperativeHandle Hook

```typescriptreact
useImperativeHandle(|, () => ({
  return {
    |() {
      |
    }
  }
}), [|])
```

#### `rul` - useLayoutEffect Hook

```typescriptreact
useLayoutEffect(() => {
  |
}, [|])
```

#### `rum` - useMemo Hook

```typescriptreact
const | = useMemo(() => |, [|])
```

#### `rurd` - useReducer Hook

```typescriptreact
const [|, |] = useReducer(|, |, |)
```

#### `rurf` - useRef Hook

```typescriptreact
const | = useRef|(|)
```

#### `rust` - useState Hook

```typescriptreact
const [|, set|] = useState|(|)
```

#### `rusy` - useSyncExternalStore Hook

```typescriptreact
const | = useSyncExternalStore(|, |, |)
```

#### `rut` - useTransition Hook

```typescriptreact
const [|, |] = useTransition(|, |)
```
