## happy path
  - utter_greet
* greet
  - utter_greet
* help
  - utter_help
* look
  - action_look
* pickup
  - action_pickup
  - slot{"key": true}
* pickup
  - action_pickup
  - slot{"poster": true}
* inventory
  - action_inventory
* use
  - action_use

## also happy path
* greet
  - utter_greet
* inventory
  - action_inventory
* look
  - action_look
* pickup
  - action_pickup
  - slot{"poster": true}
* inventory
  - action_inventory
* pickup
  - action_pickup
  - slot{"key": true}
* inventory
  - action_inventory
* look
  - action_look
* use
  - action_use
