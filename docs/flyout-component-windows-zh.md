---
id: flyout-component
title: Flyout
---

# Reference

## Props

继承 [View Props](https://reactnative.dev/docs/view#props).

### horizonalOffset

水平偏移像素

| type | required |
|:--|:--|
| number | No |

### verticalOffset

垂直偏移像素

| type | required |
|:--|:--|
| number | No |

### isLightDismissEnabled

Whether or not the flyout will close if the user clicks away from the popup.

Set to false if you want your flyout to be modal.

| type | required |
|:--|:--|
| bool | No |

### isOverlayEnabled

Specifies whether the area outside the flyout is darkened.

| type | required |
|:--|:--|
| bool | No |

### isOpen

A boolean that returns true when the flyout is active/open, and false when it's not.

| type | required |
|:--|:--|
| bool | No |

### onDismiss

An event that fires when the flyout is dismissed.

This must update the [`isOpen`](#isopen) property.

| type | required |
|:--|:--|
| function | Yes |

### target

A component that the flyout is attached to and will show from when [`isOpen`](#isopen) is true.

| type | required |
|:--|:--|
| React.ReactNode | Yes |

### placement

The relative placement of the flyout in relation to the [`target`](#target) set.

Accepted placements value types are:

- `top`
- `bottom`
 - `left`
 - `right`
 - `full`
 - `top-edge-aligned-left`
 - `top-edge-aligned-right`
 - `bottom-edge-aligned-left`
 - `bottom-edge-aligned-right`
 - `left-edge-aligned-top`
 - `right-edge-aligned-top`
 - `left-edge-aligned-bottom`
 - `right-edge-aligned-bottom`

| type | required |
|:--|:--|
| type | No |
