# React Native Japan Meetup

[イベントURL](https://react-native-meetup.connpass.com/event/60764/)

## 目次
1. React Nativeで楽しくて幸せなサービス開発
2. React Native導入の検討
3. １ヶ月でのアプリ作り〜地雷を踏み越えて！〜
4. Expoを使って開発して実際にアプリを公開して得られた知見
5. React Native into Expo!


## 各内容
### 1. React Nativeで楽しくて幸せなサービス開発
#### web tool活用
eslint
flow
mocha
- jest
https://facebook.github.io/jest/
- lerna
https://lernajs.io/
monorepoの実現
http://qiita.com/kimamula/items/0b4dff363933bfe74506

#### Library
- formik
- react-native push notification
OS間の違いはwrapper
- React Navive Vector icons
- redux saga
- React native router flux (old)
v4: based on React Navigation API
~v3: experimental-navigation
- React native drawer (old)
- React natigation (recommeded)
->routing library

### 2. React Native導入の検討
[engoo]()で実施したReact Native導入時の対応について  
- APIではエンティティごとにVersion管理
- required versionに齟齬が生まれてしまった場合は、refleshを求めるポップアップを表示した後、reflesh処理を実施。
- webRTCでのビデオ電話

### 3. １ヶ月でのアプリ作り〜地雷を踏み越えて！〜
#### Library
- React Native Interactive
- React Native Navigation
Android / iOS が同一コードが動かない
- React Native Debuger
- react-native-chart
https://www.npmjs.com/package/react-native-chart


### 4. Expoを使って開発して実際にアプリを公開して得られた知見
- expo.io
簡単にビルドできるGUIアプリケーション  
[https://expo.io/tools](https://expo.io/tools)  
- Native modulesが使えない。  
- Deep link->Auth、
- expoサーバへの通信が必要のため、初期ロード時にオンラインである必要がある

### 5. React Native into Expo!
