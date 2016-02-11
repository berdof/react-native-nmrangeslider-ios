# Native iOS multi slider component for React Native

Native iOS multi slider component for React Native with two markers based on [NMRangeSlider](https://github.com/mvelikov/NMRangeSlider).

[react-native-multi-slider](https://github.com/JackDanielsAndCode/react-native-multi-slider) 
works in javascript only which creates a noticeable lag when moving a 
slider. Because NMRangeSlider is implemented as a native module there is no lag in this version.

![slider-example](https://cloud.githubusercontent.com/assets/133832/12846584/a28dc36e-cc0d-11e5-9a70-dcc4445e72b6.gif)


# Installation

```
npm install --save react-native-nmrangeslider-ios
```

Follow the [procedure to link the library in XCode](https://facebook.github.io/react-native/docs/linking-libraries-ios.html#manual-linking) 
or run `rnpm link react-native-nmrangeslider-ios` using [rnpm](https://github.com/rnpm/rnpm).


Then drag and drop the "DefaultTheme7" folder from `node_modules/react-native-nmrangeslider-ios/` to your
XCode Resources folder. Select "copy files if necessary" and link them to your project. 

# Usage example

```
import NMRangeSliderIOS from 'react-native-nmrangeslider-ios';

<NMRangeSliderIOS
  minimumValue={0}
  maximumValue={99}
  lowerValue={10}
  upperValue={80}
  onChange={this.onChangeAge}
  style={{ width: 300, height: 50 }}
/>
```

# License

Copyright 2016 Enrise BV
Licensed under the MIT License.

