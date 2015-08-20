#react-native-draggable-drawer

DraggableDrawer is a component for react-native, it allows you have a vertical draggable drawer view that you can drag up or drag down. So, if you drag and release that component, then it keeps moving until reach  either initial position or container border.  

## Example
### [draggable-drawer-image-bouncing](https://github.com/llanox/react-native-draggable-drawer/blob/master/DraggableDrawer/DemoScreen.js)

![react-native-draggable-drawer](http://i.imgur.com/AequjyD.gif)

### Installation

```bash
$ npm i react-native-draggable-drawer --save
```

### Properties

#### Basic

| Prop  | Default  | Type | Description |
| :------------ |:---------------:| :---------------:| :-----|
| onDragDown | undefined | `function` | If you pass a function as parameter it will be notified when the user drag down the drawer  |
| onRelease | undefined | `function` | If you pass a function as parameter it will be notified when the user release the drawer after drag it |
| initialDrawerSize | 0 | `number` | It's the initial position or size for Drawer component. |
| renderContainerView | undefined | `View` | Pass as parameter a renderable react component to show as container. |
| renderDrawerView | undefined | `View` | Pass as parameter a renderable react component to show as drawer. |


