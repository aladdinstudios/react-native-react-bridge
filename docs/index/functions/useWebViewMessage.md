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

[src/native/index.ts:28](https://github.com/aladdinstudios/react-native-react-bridge/blob/655f877ebb3bf619b210aad74eeb5292e18e24cb/src/native/index.ts#L28)
