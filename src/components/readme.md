# Currency Textfield for Material UI v5 (MUI) [![npm version](https://badge.fury.io/js/@puhl%2Fmui-currency-textfield.svg)](https://badge.fury.io/js/@puhl%2Fmui-currency-textfield)

[View on Github](https://github.com/puhlup/mui-currency-textfield)
## Installation
 ```bash
 npm install @puhl/mui-currency-textfield --save
```
## Usage

```html
import React from 'react'
import CurrencyTextField from '@puhl/mui-currency-textfield'

export default function MyComponent() {

  const [value, setValue] = React.useState();

  return (
    <CurrencyTextField
		label="Amount"
		variant="standard"
		value={value}
		currencySymbol="$"
		outputFormat="string"
		onChange={(event, value)=> setValue(value)}
    />
  );
}
```
