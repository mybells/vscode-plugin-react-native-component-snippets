# React Native Component Snippets extension for Visual Studio Code

react-native内置组件标签、API代码自动补全。react文件Class结构、Hook结构、常用生命周期、常用Hook代码自动补全。

## Install
在Extensions(`Ctrl+Shift+X`)搜索`React Native Component Snippets`安装。

## Snippets List

### 视图组件
|         Trigger Key         | Element Tag                  |
| :-------------------------: | :--------------------------- |
|    `$ActivityIndicator`     | `<ActivityIndicator>`        |
|          `$Button`          | `<Button>`                   |
|      `$DatePickerIOS`       | `<DatePickerIOS>`            |
|   `$DrawerLayoutAndroid`    | `<DrawerLayoutAndroid>`      |
|         `$FlatList`         | `<FlatList>`                 |
|          `$Image`           | `<Image>`                    |
|     `$ImageBackground`      | `<ImageBackground>`          |
|   `$KeyboardAvoidingView`   | `<KeyboardAvoidingView>`     |
|      `$MaskedViewIOS`       | `<MaskedViewIOS>`            |
|          `$Modal`           | `<Modal>`                    |
|          `$Picker`          | `<Picker>`                   |
|    `$ProgressBarAndroid`    | `<ProgressBarAndroid>`       |
|     `$ProgressViewIOS`      | `<ProgressViewIOS>`          |
|      `$RefreshControl`      | `<RefreshControl>`           |
|       `$SafeAreaView`       | `<SafeAreaView>`             |
|        `$ScrollView`        | `<ScrollView>`               |
|       `$SectionList`        | `<SectionList>`              |
|   `$SegmentedControlIOS`    | `<SegmentedControlIOS>`      |
|          `$Slider`          | `<Slider>`                   |
|        `$StatusBar`         | `<StatusBar>`                |
|        `$StyleSheet`        | `<StyleSheet>`               |
|          `$Switch`          | `<Switch>`                   |
|           `$Text`           | `<Text>`                     |
|        `$TextInput`         | `<TextInput>`                |
|    `$TouchableHighlight`    | `<TouchableHighlight>`       |
| `$TouchableNativeFeedback`  | `<TouchableNativeFeedback>`  |
|     `$TouchableOpacity`     | `<TouchableOpacity>`         |
| `$TouchableWithoutFeedback` | `<TouchableWithoutFeedback>` |
|           `$View`           | `<View>`                     |
|     `$ViewPagerAndroid`     | `<ViewPagerAndroid>`         |
|     `$VirtualizedList`      | `<VirtualizedList>`          |
|         `$WebView`          | `<WebView>`                  |

### API组件
|      Trigger Key      | Element Tag                      |
| :-------------------: | :------------------------------- |
|       `$Alert`        | `Alert.alert()`                  |
|      `$Animated`      | `Animated.timing()`              |
|    `$BackHandler`     | `BackHandler.addEventListener()` |
|    `$BackHandler`     | `BackHandler.addEventListener()` |
|  `$AsyncStorageGet`   | `AsyncStorage.getItem()`         |
|  `$AsyncStorageSet`   | `AsyncStorage.setItem()`         |
| `$AsyncStorageRemove` | `AsyncStorage.removeItem()`      |
|    `$ClipboardGet`    | `Clipboard.getString()`          |
|    `$ClipboardSet`    | `Clipboard.setString()`          |
|     `$Dimensions`     | `Dimensions.get('window')`       |
|      `$Linking`       | ` Linking.openURL()`             |

### React组件
|      Trigger Key       | Element Tag                                           |
| :--------------------: | :---------------------------------------------------- |
|         `$cwm`         | `componentWillMount = () => {}`                       |
|         `$cdm`         | `componentDidMount = () => {}`                        |
|         `$cwr`         | `componentWillReceiveProps = (nextProps) => {}`       |
|         `$scu`         | `shouldComponentUpdate = (nextProps,nextState) => {}` |
|        `$cwup`         | `componentWillUpdate = (nextProps, nextState) => {}`  |
|        `$cdup`         | `componentDidUpdate = (prevProps, prevState) => {}`   |
|        `$cwun`         | `componentWillUnmount = () => {}`                     |
|       `$render`        | `render() { return () }`                              |
|      `$setState`       | `this.setState({})`                                   |
|      `$useState`       | `const [state, setstate] = useState()`                |
|      `$useEffect`      | `useEffect(()=>{},[])`                                |
|     `$useContext`      | `const context = useContext()`                        |
|     `$useReducer`      | `const [state, dispatch] = useReducer()`              |
|     `$useCallback`     | `useCallback(()=>{},[])`                              |
|       `$useMemo`       | `useMemo(()=>{})`                                     |
|       `$useRef`        | `const ref = useRef()`                                |
| `$useImperativeHandle` | `useImperativeHandle()`                               |
|    `$useDebugValue`    | `useDebugValue()`                                     |
|   `$useLayoutEffect`   | `useLayoutEffect(()=>{},[])`                          |
|     `$useSelector`     | `const state = useSelector(state =>{})`               |
|     `$useDispatch`     | `const dispatch = useDispatch()`                      |
|     `$constructor`     | `react的constructor`                                  |
|      `$fragment`       | `<></>`                                               |
|      `$createRef`      | `this.ref = React.createRef()`                        |
|    `$createPortal`     | `ReactDOM.createPortal(child, container)`             |
|        `$style`        | `style={{}}`                                          |
|       `$import`        | `import xxx from 'xxx'`                               |
|         `$clg`         | `console.log()`                                       |

### 架构组件
|  Trigger Key  | Element Tag               |
| :-----------: | :------------------------ |
| `$reactclass` | `react的Class组件`        |
| `$reacthook`  | `react的Hook组件`         |
|  `$rnclass`   | `react-native的Class组件` |
|   `$rnhook`   | `react-native的Hook组件`  |