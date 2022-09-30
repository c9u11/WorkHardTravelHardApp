# WorkHardTravelHardApp

## 개요

이 프로젝트는 NomadCoder의 RN 2번째 강의입니다.

## ReactNative

### Component

#### TouchableOpacity

Touch를 감지하는 태그, 기본적으로 opacity가 변경된다.

다양한 옵션을 통해 이벤트 핸들러의 역할을 수행할 수 있다.

- onPress
- onPressIn
- onPressOut
- onLongPress

```react
<TouchableOpacity onPress={()=>console.log("Press!!!")}>
	<Text>Test</Text>
</TouchableOpacity>
```

#### TouchableHighlight

Touch를 감지하는 태그, underlayColor Option을 통해 배경색이 변경된다.

```react
<TouchableHighlight underlayColor="red">
	<Text>Test</Text>
</TouchableHighlight>
```

#### TouchableWithoutFeedback

Touch를 감지하는 태그, 위 태그들과는 다르게 기본 애니메이션이 없다.

```react
<TouchableWithoutFeedback>
	<Text>Test</Text>
</TouchableWithoutFeedback>
```

#### Pressable

가장 최근에 나온 기본 태그, TouchableWithoutFeedback 태그의 상위호환이라고 보면 된다.