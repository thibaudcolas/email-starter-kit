---
displayName: preheader
classBase: preheader
schema:
  todo:
    type: string
    description: TODO
usage:
  - class: .preheader
    required: True
    elements:
      - table
    outcome: Defines the preheader component
flavours:
  - title: Base
    status: production
    states:
      - title: Default
        data:
          todo: todo
---