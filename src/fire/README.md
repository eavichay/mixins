# 

## Methods

| Method | Type                                             | Description                                      |
|--------|--------------------------------------------------|--------------------------------------------------|
| `fire` | `(type: string, detail: any, { bubbles, composed }?: EventInit \| undefined): boolean` | Fires a CustomEvent with an optional supplied detail.<br /><br />Fired events do not bubble and are not composed by default,<br />Pass an EventInit in the third argument to set `bubbles` or `composed`.<br /><br />**type**: CustomEvent type<br />**detail**: detail value<br />**options**: options initializer |
