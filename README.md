# react-native-blockies
Blocky component for React-native

Wrap Webview into a View to generate blocky using ethereum-blockies module
https://github.com/ethereum/blockies/blob/master/blockies.min.js

## Use

```
import Blockies from 'react-native-blockies';

render() {
    return (
        <Blockies
            blockies={address} //string content to generate icon
            size={32} // blocky icon size
            style={{width:32, height:32}} // style of the view will wrap the icon
        />
    );
}
```
