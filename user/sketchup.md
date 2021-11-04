# SketchUp (Alpha) 🛠️

::: tip IMPORTANT ⚠️
This connector is currently in alpha with limited functionality. Sending is fairly stable, but receiving is unreliable. Please keep this in mind while testing!
:::

![example-send](./img-sketchup/sketchup-hostel-sent.png)

## Getting Started

Before using this connector, you'll need to follow our standard setup instructions to [install Speckle Manager and add a Speckle account](/user/manager).

As this connector is still in heavy development, see the [repo](https://github.com/specklesystems/speckle-sketchup) for the latest installation instructions.

## User Interface

### Sending Data

For the moment, there is only one send mode: selection.

Simply select all the objects you would like to send, then click the "Send" cube. To switch the targeted branch, click the currently selected branch and find the branch from the dropdown menu.

![sending-with-sketchup-img](./img-sketchup/sketchup-send.png)

See the gif below for the full process.

![sending-with-sketchup-gif](./img-sketchup/sketchup-send.gif)

### Receiving Data

Receiving is currently unreliable and not fully supported. SketchUp models sent to Speckle will not always be received due to some current issues with receiving components/blocks.

However, meshes and lines that are not contained in components/blocks should be received as expected.

![receiving-with-sketchup-img](./img-sketchup/sketchup-receive.png)

See the full process of receiving a Rhino model in this snazzy gif

![sketchup-receive](https://user-images.githubusercontent.com/7717434/140315797-089bb936-fb3d-4c05-9e4b-687e0835bb68.gif)


### Accounts

Your Speckle accounts should be added via [Speckle Manager](/user/manager).

You can switch between your accounts by clicking your profile image and selecting it from the popup menu.

![sketchup-switch-accounts](https://user-images.githubusercontent.com/7717434/140301242-f4b04004-d1f6-4946-8802-dc95d3245746.gif)


## Supported Elements

See [SketchUp Support Tables](/user/support-tables.html#sketchup)