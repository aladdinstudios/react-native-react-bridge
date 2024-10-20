[**API**](../../API.md) • **Docs**

***

# Function: useWebViewMessage()

> **useWebViewMessage**\<`T`\>(`onSubscribe`): `object`

A hook to subscribe messages from WebView.

## Type Parameters

• **T**

## Parameters

• **onSubscribe**

## Returns

`object`

### ref

> **ref**: `RefObject`\<`WebView`\<`object`\>\>

### onMessage()

> **onMessage**: (`event`) => `void`

#### Parameters

• **event**: `WebViewMessageEvent`

#### Returns

`void`

### emit()

> **emit**: (`message`) => `void`

#### Parameters

• **message**: [`ReactNativeMessage`](../interfaces/ReactNativeMessage.md)\<`T`\>

#### Returns

`void`

## Defined in

[src/native/index.ts:28](https://github.com/aladdinstudios/react-native-react-bridge/blob/898909b5e203475f41b87ce030a63736af99841d/src/native/index.ts#L28)
