# Typescript React Snippets

1. Insert a Hook based React Component for Dash Case Based Filenames

If you use dash-cased based filenames for your React components, this is the snippet for you.
Insert with `tsrcd` in any `.tsx` file.

For example, if your file is called `typescript-react-example.tsx` and you insert this snippet, you'll get this:

```
import React from 'react'

const TypescriptReactExample: React.FC<TypescriptReactExampleProps> = ({ ...props }) => {
    return null
}
export type TypescriptReactExampleProps = {
}

export default TypescriptReactExample
```
