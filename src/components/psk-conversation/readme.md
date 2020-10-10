# psk-conversation



<!-- Auto Generated Below -->


## Properties

| Property     | Attribute     | Description | Type     | Default                      |
| ------------ | ------------- | ----------- | -------- | ---------------------------- |
| `configPath` | `config-path` |             | `string` | `"conversation-config.json"` |


## Dependencies

### Depends on

- psk-label
- psk-button
- [psk-floating-button-group](../psk-floating-button-group)
- psk-container
- psk-icon

### Graph
```mermaid
graph TD;
  psk-conversation --> psk-label
  psk-conversation --> psk-button
  psk-conversation --> psk-floating-button-group
  psk-conversation --> psk-container
  psk-conversation --> psk-icon
  psk-floating-button-group --> psk-button-group
  psk-floating-button-group --> psk-grid
  psk-floating-button-group --> psk-button
  psk-floating-button-group --> psk-icon
  psk-button-group --> psk-icon
  psk-container --> psk-page-loader
  style psk-conversation fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
