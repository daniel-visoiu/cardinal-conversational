# psk-floating-button-group



<!-- Auto Generated Below -->


## Properties

| Property   | Attribute  | Description | Type                     | Default |
| ---------- | ---------- | ----------- | ------------------------ | ------- |
| `backdrop` | `backdrop` |             | `boolean`                | `false` |
| `buttons`  | --         |             | `FloatingButtonConfig[]` | `[]`    |
| `opened`   | `opened`   |             | `boolean`                | `false` |


## Dependencies

### Used by

 - [psk-conversation](../psk-conversation)

### Depends on

- psk-button-group
- psk-grid
- psk-button
- psk-icon

### Graph
```mermaid
graph TD;
  psk-floating-button-group --> psk-button-group
  psk-floating-button-group --> psk-grid
  psk-floating-button-group --> psk-button
  psk-floating-button-group --> psk-icon
  psk-button-group --> psk-icon
  psk-conversation --> psk-floating-button-group
  style psk-floating-button-group fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
