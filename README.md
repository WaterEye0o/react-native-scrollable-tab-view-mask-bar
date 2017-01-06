## react-native-scrollable-tab-view-mask-bar
[![npm version](https://badge.fury.io/js/react-native-scrollable-tab-view-mask-bar.svg)](https://badge.fury.io/js/react-native-scrollable-tab-view-mask-bar)
this component is a custom component of the react-native-scrollable-tab-view repository ,so I suggest you use this component and the combination of react-native-scrollable-tab-view.

## Install

1. Run `npm install react-native-scrollable-tab-mask-bar --save`
2. Run `npm install react-native-scrollable-tab-view --save`

## Usage

```
var ScrollableTabView = require('react-native-scrollable-tab-view');
var MaskTabBar = require('react-native-scrollable-tab-view-mask-bar');

var App = React.createClass({
  render() {
    return (
      <ScrollableTabView renderTabBar={() => <MaskTabBar someProp={'here'} showMask={true} maskMode='light' />}>
        <ReactPage tabLabel="React" />
        <FlowPage tabLabel="Flow" />
        <JestPage tabLabel="Jest" />
      </ScrollableTabView>
    );
  }
});
```

## Demo

<a href="https://raw.githubusercontent.com/WaterEye0o/react-native-scrollable-tab-mask-bar/master/demo_images/facebook_tabbar.gif"><img src="https://raw.githubusercontent.com/WaterEye0o/react-native-scrollable-tab-mask-bar/master/demo_images/facebook_tabbar.gif" width="350"></a>
