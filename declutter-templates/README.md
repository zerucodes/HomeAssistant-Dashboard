How to use declutter cards:
1. Follow installation 
    https://github.com/custom-cards/decluttering-card
2. Add templates to any dashboard (see declutter-tempaltes.yaml for indentaiton example dashboard config)

3. Use any decluttering tempalte:

```
type: custom:decluttering-card
template: device_details
variables:
  - device: Apollo
```
![image](https://github.com/user-attachments/assets/01bf8787-6aa5-40a2-a82d-45b4df5b7142)




```
type: custom:decluttering-card
template: area_details
variables:
  - area: sunroom
```
![image](https://github.com/user-attachments/assets/78bd8e80-53d8-46ec-afbb-4d0de09d30bf)




```
type: custom:decluttering-card
template: quick_play_grid
variables:
  - media_player: media_player.apollo_2
```
![image](https://github.com/user-attachments/assets/b93efc36-f49f-41d3-93a2-564b7cc69697)




Special Note:
* I rely on a few dashboard input_buttons (created as helper)  to hide verbose configs
    * input_boolean.dashboard_show_details
    * input_boolean.dashboard_show_lights
    * input_boolean.dashboard_show_automations
