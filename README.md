# blueprints
Some Home Assistant blueprints I have created

## Cabinet lights
This blueprint is used to control lights inside a cabinet. They turn on when the door sensor triggers and turn back off once the door is closed again. Of course it can be used in other similar situations. The general setup is described in [my blog here](https://thesmarthomejourney.com/2020/07/07/diy-smart-wardrobe-lights/).

## Motion brightness light
This blueprint extends the included motion sensor automation from Home Assistant by adding a brightness sensor. The lights will only turn on if the brightness is lower than a certain threshold you can provide or if it night (after sunset, before sunrise). That way you can avoid using hardcoded times to activate your lights. There is an in-depth explanation on my blog [here](https://thesmarthomejourney.com/2021/04/19/ultimate-smart-light-system/).  