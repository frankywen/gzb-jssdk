[@gdjiami/gzb-jssdk](../README.md) > ["MobileApi"](../modules/_mobileapi_.md) > [MobileApi](../classes/_mobileapi_.mobileapi.md)



# Class: MobileApi

## Hierarchy


↳  [Api](_api_.api.md)

**↳ MobileApi**







## Index

### Properties

* [closeCallback](_mobileapi_.mobileapi.md#closecallback)
* [gobackCallback](_mobileapi_.mobileapi.md#gobackcallback)
* [isReady](_mobileapi_.mobileapi.md#isready)
* [mobileBridge](_mobileapi_.mobileapi.md#mobilebridge)
* [instance](_mobileapi_.mobileapi.md#instance)


### Methods

* [Dialog](_mobileapi_.mobileapi.md#dialog)
* [QRcode](_mobileapi_.mobileapi.md#qrcode)
* [_teardownBeforeUnloadWatcher](_mobileapi_.mobileapi.md#_teardownbeforeunloadwatcher)
* [addListener](_mobileapi_.mobileapi.md#addlistener)
* [apiInfos](_mobileapi_.mobileapi.md#apiinfos)
* [checkBarWatcher](_mobileapi_.mobileapi.md#checkbarwatcher)
* [chooseImg](_mobileapi_.mobileapi.md#chooseimg)
* [date](_mobileapi_.mobileapi.md#date)
* [emit](_mobileapi_.mobileapi.md#emit)
* [exit](_mobileapi_.mobileapi.md#exit)
* [exitApp](_mobileapi_.mobileapi.md#exitapp)
* [getBackButtonVisible](_mobileapi_.mobileapi.md#getbackbuttonvisible)
* [getCloseButtonVisible](_mobileapi_.mobileapi.md#getclosebuttonvisible)
* [getLanguage](_mobileapi_.mobileapi.md#getlanguage)
* [getList](_mobileapi_.mobileapi.md#getlist)
* [getListenerLength](_mobileapi_.mobileapi.md#getlistenerlength)
* [getLoc](_mobileapi_.mobileapi.md#getloc)
* [getLocation](_mobileapi_.mobileapi.md#getlocation)
* [getMoreButtonVisible](_mobileapi_.mobileapi.md#getmorebuttonvisible)
* [goback](_mobileapi_.mobileapi.md#goback)
* [hideBar](_mobileapi_.mobileapi.md#hidebar)
* [innerAddEventListener](_mobileapi_.mobileapi.md#inneraddeventlistener)
* [locationTo](_mobileapi_.mobileapi.md#locationto)
* [mail](_mobileapi_.mobileapi.md#mail)
* [once](_mobileapi_.mobileapi.md#once)
* [openContact](_mobileapi_.mobileapi.md#opencontact)
* [openDialog](_mobileapi_.mobileapi.md#opendialog)
* [phone](_mobileapi_.mobileapi.md#phone)
* [removeAllListener](_mobileapi_.mobileapi.md#removealllistener)
* [removeListener](_mobileapi_.mobileapi.md#removelistener)
* [scanQRCode](_mobileapi_.mobileapi.md#scanqrcode)
* [selectContact](_mobileapi_.mobileapi.md#selectcontact)
* [selectSession](_mobileapi_.mobileapi.md#selectsession)
* [setBackButtonVisible](_mobileapi_.mobileapi.md#setbackbuttonvisible)
* [setBarButtonVisible](_mobileapi_.mobileapi.md#setbarbuttonvisible)
* [setBarColor](_mobileapi_.mobileapi.md#setbarcolor)
* [setBarVisible](_mobileapi_.mobileapi.md#setbarvisible)
* [setCloseButtonVisible](_mobileapi_.mobileapi.md#setclosebuttonvisible)
* [setMoreButtonVisible](_mobileapi_.mobileapi.md#setmorebuttonvisible)
* [setTitle](_mobileapi_.mobileapi.md#settitle)
* [setUpBeforeUnloadWatcher](_mobileapi_.mobileapi.md#setupbeforeunloadwatcher)
* [setUpBridge](_mobileapi_.mobileapi.md#setupbridge)
* [setUpGobackWatcher](_mobileapi_.mobileapi.md#setupgobackwatcher)
* [settingBar](_mobileapi_.mobileapi.md#settingbar)
* [setupBarWatcher](_mobileapi_.mobileapi.md#setupbarwatcher)
* [setupEventWatcher](_mobileapi_.mobileapi.md#setupeventwatcher)
* [shareTo](_mobileapi_.mobileapi.md#shareto)
* [showBar](_mobileapi_.mobileapi.md#showbar)
* [showContact](_mobileapi_.mobileapi.md#showcontact)
* [sms](_mobileapi_.mobileapi.md#sms)
* [teardown](_mobileapi_.mobileapi.md#teardown)
* [teardownEventWatcher](_mobileapi_.mobileapi.md#teardowneventwatcher)
* [url](_mobileapi_.mobileapi.md#url)
* [watchListener](_mobileapi_.mobileapi.md#watchlistener)
* [getInstance](_mobileapi_.mobileapi.md#getinstance)



---

## Properties
<a id="closecallback"></a>

### «Private» closeCallback

**●  closeCallback**:  *function* 

*Defined in [MobileApi.ts:23](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L23)*


#### Type declaration
(): `void`


*Defined in [MobileApi.ts:23](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L23)*





**Returns:** `void`






___

<a id="gobackcallback"></a>

### «Private» gobackCallback

**●  gobackCallback**:  *function* 

*Defined in [MobileApi.ts:24](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L24)*


#### Type declaration
(): `void`


*Defined in [MobileApi.ts:24](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L24)*





**Returns:** `void`






___

<a id="isready"></a>

###  isReady

**●  isReady**:  *`boolean`*  = false

*Inherited from [Api](_api_.api.md).[isReady](_api_.api.md#isready)*

*Defined in [Api.ts:93](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L93)*





___

<a id="mobilebridge"></a>

### «Private» mobileBridge

**●  mobileBridge**:  *[MobileBridge](_bridge_mobilebridge_.mobilebridge.md)* 

*Defined in [MobileApi.ts:22](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L22)*





___

<a id="instance"></a>

### «Static»«Private» instance

**●  instance**:  *[Api](_api_.api.md)* 

*Defined in [MobileApi.ts:21](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L21)*





___


## Methods
<a id="dialog"></a>

###  Dialog

► **Dialog**(params: *[DialogParams](../interfaces/_protocol_.dialogparams.md)⎮`DialogType.GroupChat`⎮`DialogType.Chat`⎮`DialogType.Announcement`*, id: *`string`*): `void`




*Inherited from [Api](_api_.api.md).[Dialog](_api_.api.md#dialog)*

*Defined in [Api.ts:627](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L627)*



打开会话框
*__platform__*: *

*__deprecated__*: 使用openDialog代替

*__alias__*: openDialog



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| params | [DialogParams](../interfaces/_protocol_.dialogparams.md)⎮`DialogType.GroupChat`⎮`DialogType.Chat`⎮`DialogType.Announcement`   |  - |
| id | `string`   |  - |





**Returns:** `void`





___

<a id="qrcode"></a>

###  QRcode

► **QRcode**(needResult: *`boolean`*, callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[QRCodeResponse](../interfaces/_protocol_.qrcoderesponse.md)*): `void`




*Inherited from [Api](_api_.api.md).[QRcode](_api_.api.md#qrcode)*

*Defined in [Api.ts:585](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L585)*



扫二维码
*__platform__*: `Android` | `IOS`

*__alias__*: scanQRCode

*__deprecated__*: 使用`scanQRCode`代替



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| needResult | `boolean`   |  - |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[QRCodeResponse](../interfaces/_protocol_.qrcoderesponse.md)   |  - |





**Returns:** `void`





___

<a id="_teardownbeforeunloadwatcher"></a>

### «Private» _teardownBeforeUnloadWatcher

► **_teardownBeforeUnloadWatcher**(): `void`




*Defined in [MobileApi.ts:171](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L171)*





**Returns:** `void`





___

<a id="addlistener"></a>

###  addListener

► **addListener**(eventType: *[EventType](../modules/_api_.md#eventtype)*, callback: *[EventCallback](../modules/_api_.md#eventcallback)*, context?: *`any`*): function




*Inherited from [Api](_api_.api.md).[addListener](_api_.api.md#addlistener)*

*Overrides [EventEmitter](_eventemitter_.eventemitter.md).[addListener](_eventemitter_.eventemitter.md#addlistener)*

*Defined in [Api.ts:96](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L96)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| eventType | [EventType](../modules/_api_.md#eventtype)   |  - |
| callback | [EventCallback](../modules/_api_.md#eventcallback)   |  - |
| context | `any`   |  - |





**Returns:** function





___

<a id="apiinfos"></a>

###  apiInfos

► **apiInfos**(callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[APIInfosResponseOld](../interfaces/_protocol_.apiinfosresponseold.md)*): `void`

► **apiInfos**(): `Promise`.<[APIInfosResponse](../interfaces/_protocol_.apiinfosresponse.md)>




*Inherited from [Api](_api_.api.md).[apiInfos](_api_.api.md#apiinfos)*

*Defined in [Api.ts:496](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L496)*



获取应用和可用API信息  
FIXME: 待测试
*__platform__*: *

*__alias__*: getList



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[APIInfosResponseOld](../interfaces/_protocol_.apiinfosresponseold.md)   |  - |





**Returns:** `void`




*Inherited from [Api](_api_.api.md).[apiInfos](_api_.api.md#apiinfos)*

*Defined in [Api.ts:497](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L497)*





**Returns:** `Promise`.<[APIInfosResponse](../interfaces/_protocol_.apiinfosresponse.md)>





___

<a id="checkbarwatcher"></a>

### «Private» checkBarWatcher

► **checkBarWatcher**(name: *"goback"⎮"close"*, eventName: *`string`*): `void`




*Defined in [MobileApi.ts:121](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L121)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| name | "goback"⎮"close"   |  - |
| eventName | `string`   |  - |





**Returns:** `void`





___

<a id="chooseimg"></a>

###  chooseImg

► **chooseImg**(params?: *[ChooseImgParams](../interfaces/_protocol_.chooseimgparams.md)*): `Promise`.<[ChooseImgResponse](../interfaces/_protocol_.chooseimgresponse.md)>

► **chooseImg**(params?: *[ChooseImgParams](../interfaces/_protocol_.chooseimgparams.md)*, callback?: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[ChooseImgResponseOld](../interfaces/_protocol_.chooseimgresponseold.md)*): `void`




*Inherited from [Api](_api_.api.md).[chooseImg](_api_.api.md#chooseimg)*

*Defined in [Api.ts:644](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L644)*



选择图片
*__platform__*: *



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| params | [ChooseImgParams](../interfaces/_protocol_.chooseimgparams.md)   |  - |





**Returns:** `Promise`.<[ChooseImgResponse](../interfaces/_protocol_.chooseimgresponse.md)>




*Inherited from [Api](_api_.api.md).[chooseImg](_api_.api.md#chooseimg)*

*Defined in [Api.ts:645](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L645)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| params | [ChooseImgParams](../interfaces/_protocol_.chooseimgparams.md)   |  - |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[ChooseImgResponseOld](../interfaces/_protocol_.chooseimgresponseold.md)   |  - |





**Returns:** `void`





___

<a id="date"></a>

###  date

► **date**(): `void`




*Inherited from [Api](_api_.api.md).[date](_api_.api.md#date)*

*Defined in [Api.ts:389](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L389)*



日期选择器
*__deprecated__*: 很少使用，而且不是所有平台都支持





**Returns:** `void`





___

<a id="emit"></a>

###  emit

► **emit**(eventType: *`string`*, data?: *`any`*): `any`[]




*Inherited from [EventEmitter](_eventemitter_.eventemitter.md).[emit](_eventemitter_.eventemitter.md#emit)*

*Defined in [EventEmitter.ts:169](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/EventEmitter.ts#L169)*



触发事件

> 注意：所有回调都是被同步调用的


**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| eventType | `string`   |  事件类型 |
| data | `any`   |  自定义数据 |





**Returns:** `any`[]
返回一个数组，表示所有订阅者回调中返回的值






___

<a id="exit"></a>

###  exit

► **exit**(): `void`




*Inherited from [Api](_api_.api.md).[exit](_api_.api.md#exit)*

*Defined in [Api.ts:369](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L369)*



关闭web应用窗口




**Returns:** `void`





___

<a id="exitapp"></a>

###  exitApp

► **exitApp**(): `void`




*Inherited from [Api](_api_.api.md).[exitApp](_api_.api.md#exitapp)*

*Defined in [Api.ts:381](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L381)*



关闭web应用窗口
*__platform__*: *

*__deprecated__*: 使用exit代替

*__alias__*: exit





**Returns:** `void`





___

<a id="getbackbuttonvisible"></a>

###  getBackButtonVisible

► **getBackButtonVisible**(): `boolean`




*Defined in [MobileApi.ts:46](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L46)*





**Returns:** `boolean`





___

<a id="getclosebuttonvisible"></a>

###  getCloseButtonVisible

► **getCloseButtonVisible**(): `boolean`




*Defined in [MobileApi.ts:50](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L50)*





**Returns:** `boolean`





___

<a id="getlanguage"></a>

###  getLanguage

► **getLanguage**(callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[GetLanguageResponseOld](../interfaces/_protocol_.getlanguageresponseold.md)*): `void`

► **getLanguage**(): `Promise`.<`string`>




*Inherited from [Api](_api_.api.md).[getLanguage](_api_.api.md#getlanguage)*

*Defined in [Api.ts:741](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L741)*



获取系统语言


**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[GetLanguageResponseOld](../interfaces/_protocol_.getlanguageresponseold.md)   |  回调 |





**Returns:** `void`




*Inherited from [Api](_api_.api.md).[getLanguage](_api_.api.md#getlanguage)*

*Defined in [Api.ts:742](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L742)*





**Returns:** `Promise`.<`string`>





___

<a id="getlist"></a>

###  getList

► **getList**(callback: *function*): `void`




*Inherited from [Api](_api_.api.md).[getList](_api_.api.md#getlist)*

*Defined in [Api.ts:529](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L529)*



获取应用和可用API信息
*__deprecated__*: 使用`apiInfos`代替

*__alias__*: apiInfos



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callback | function   |  - |





**Returns:** `void`





___

<a id="getlistenerlength"></a>

###  getListenerLength

► **getListenerLength**(eventType: *`string`*): `number`




*Inherited from [EventEmitter](_eventemitter_.eventemitter.md).[getListenerLength](_eventemitter_.eventemitter.md#getlistenerlength)*

*Defined in [EventEmitter.ts:119](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/EventEmitter.ts#L119)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| eventType | `string`   |  - |





**Returns:** `number`





___

<a id="getloc"></a>

###  getLoc

► **getLoc**(callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[GetLocationResponse](../interfaces/_protocol_.getlocationresponse.md)*): `void`




*Inherited from [Api](_api_.api.md).[getLoc](_api_.api.md#getloc)*

*Defined in [Api.ts:480](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L480)*



获取当前位置
*__platform__*: *

*__alias__*: getLocation

*__deprecated__*: 使用getLocation代替



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[GetLocationResponse](../interfaces/_protocol_.getlocationresponse.md)   |  - |





**Returns:** `void`





___

<a id="getlocation"></a>

###  getLocation

► **getLocation**(callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[GetLocationResponse](../interfaces/_protocol_.getlocationresponse.md)*): `void`

► **getLocation**(options: *`Partial`.<[GetLocationOptions](../interfaces/_protocol_.getlocationoptions.md)>*, callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[GetLocationResponse](../interfaces/_protocol_.getlocationresponse.md)*): `void`

► **getLocation**(options?: *`Partial`.<[GetLocationOptions](../interfaces/_protocol_.getlocationoptions.md)>*): `Promise`.<[GetLocationResponse](../interfaces/_protocol_.getlocationresponse.md)>




*Inherited from [Api](_api_.api.md).[getLocation](_api_.api.md#getlocation)*

*Defined in [Api.ts:399](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L399)*



获取当前位置 FIXME: native 端没有错误处理
*__platform__*: `Windows` | `Android` | `IOS` | `Web`

*__alias__*: getLoc



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[GetLocationResponse](../interfaces/_protocol_.getlocationresponse.md)   |  - |





**Returns:** `void`




*Inherited from [Api](_api_.api.md).[getLocation](_api_.api.md#getlocation)*

*Defined in [Api.ts:400](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L400)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| options | `Partial`.<[GetLocationOptions](../interfaces/_protocol_.getlocationoptions.md)>   |  - |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[GetLocationResponse](../interfaces/_protocol_.getlocationresponse.md)   |  - |





**Returns:** `void`




*Inherited from [Api](_api_.api.md).[getLocation](_api_.api.md#getlocation)*

*Defined in [Api.ts:404](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L404)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| options | `Partial`.<[GetLocationOptions](../interfaces/_protocol_.getlocationoptions.md)>   |  - |





**Returns:** `Promise`.<[GetLocationResponse](../interfaces/_protocol_.getlocationresponse.md)>





___

<a id="getmorebuttonvisible"></a>

###  getMoreButtonVisible

► **getMoreButtonVisible**(): `boolean`




*Defined in [MobileApi.ts:54](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L54)*





**Returns:** `boolean`





___

<a id="goback"></a>

###  goback

► **goback**(): `void`




*Inherited from [Api](_api_.api.md).[goback](_api_.api.md#goback)*

*Defined in [Api.ts:772](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L772)*



返回到上一页， 如果是第一页，即无法回退了， 将关闭应用




**Returns:** `void`





___

<a id="hidebar"></a>

###  hideBar

► **hideBar**(): `void`




*Inherited from [Api](_api_.api.md).[hideBar](_api_.api.md#hidebar)*

*Defined in [Api.ts:328](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L328)*



隐藏Bar
*__platform__*: `Android` | `IOS`





**Returns:** `void`





___

<a id="inneraddeventlistener"></a>

### «Protected» innerAddEventListener

► **innerAddEventListener**(eventType: *`string`*, callback: *function*): function




*Inherited from [Api](_api_.api.md).[innerAddEventListener](_api_.api.md#inneraddeventlistener)*

*Defined in [Api.ts:807](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L807)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| eventType | `string`   |  - |
| callback | function   |  - |





**Returns:** function





___

<a id="locationto"></a>

###  locationTo

► **locationTo**(params: *[LocationToParams](../interfaces/_protocol_.locationtoparams.md)⎮`string`*): `void`




*Inherited from [Api](_api_.api.md).[locationTo](_api_.api.md#locationto)*

*Defined in [Api.ts:189](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L189)*



打开指定链接
*__platform__*: `Windows` | `Android` | `IOS` | `Web`

*__alias__*: url



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| params | [LocationToParams](../interfaces/_protocol_.locationtoparams.md)⎮`string`   |  请求参数，可以是字符串或对象， showMode 为inner时以应用内webview形式打开为outer时使用系统浏览器打开, 默认为outer |





**Returns:** `void`





___

<a id="mail"></a>

###  mail

► **mail**(email: *`string`*): `void`




*Inherited from [Api](_api_.api.md).[mail](_api_.api.md#mail)*

*Defined in [Api.ts:168](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L168)*



发送邮件
*__platform__*: `Windows` | `Android` | `IOS` | `Web`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| email | `string`   |  邮箱地址 |





**Returns:** `void`





___

<a id="once"></a>

###  once

► **once**(eventType: *`string`*, callback: *[Callback](../modules/_bridge_desktopbridge_.md#callback)*, context?: *`any`*): [Disposer](../modules/_eventemitter_.md#disposer)




*Inherited from [EventEmitter](_eventemitter_.eventemitter.md).[once](_eventemitter_.eventemitter.md#once)*

*Defined in [EventEmitter.ts:115](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/EventEmitter.ts#L115)*



只订阅一次事件, 事件发生后将被移除


**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| eventType | `string`   |  事件名 |
| callback | [Callback](../modules/_bridge_desktopbridge_.md#callback)   |  回调, 回调中可以返回false将会阻止后续订阅者被执行 |
| context | `any`   |  可选，回调执行的上下文 |





**Returns:** [Disposer](../modules/_eventemitter_.md#disposer)
返回一个函数，可以用于移除事件订阅






___

<a id="opencontact"></a>

###  openContact

► **openContact**(id: *`string`*): `void`




*Inherited from [Api](_api_.api.md).[openContact](_api_.api.md#opencontact)*

*Defined in [Api.ts:241](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L241)*



打开名片
*__platform__*: `Windows` | `Android` | `IOS`

*__alias__*: showContact



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| id | `string`   |  用户id |





**Returns:** `void`





___

<a id="opendialog"></a>

###  openDialog

► **openDialog**(params: *[DialogParams](../interfaces/_protocol_.dialogparams.md)*): `void`




*Inherited from [Api](_api_.api.md).[openDialog](_api_.api.md#opendialog)*

*Defined in [Api.ts:615](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L615)*



打开会话框
*__platform__*: *

*__alias__*: Dialog



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| params | [DialogParams](../interfaces/_protocol_.dialogparams.md)   |  选项+ type: 会话类型, 1 群聊 2 单聊 3公告广播+ id: 会话ID， 群组id或个人id+ messageId: //消息记录ID |





**Returns:** `void`





___

<a id="phone"></a>

###  phone

► **phone**(callNumber: *`string`*): `void`




*Inherited from [Api](_api_.api.md).[phone](_api_.api.md#phone)*

*Defined in [Api.ts:146](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L146)*



拨打手机
*__platform__*: `Windows` | `Android` | `IOS`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callNumber | `string`   |  手机号码 |





**Returns:** `void`





___

<a id="removealllistener"></a>

###  removeAllListener

► **removeAllListener**(eventType: *[EventType](../modules/_api_.md#eventtype)*): `number`




*Inherited from [Api](_api_.api.md).[removeAllListener](_api_.api.md#removealllistener)*

*Overrides [EventEmitter](_eventemitter_.eventemitter.md).[removeAllListener](_eventemitter_.eventemitter.md#removealllistener)*

*Defined in [Api.ts:117](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L117)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| eventType | [EventType](../modules/_api_.md#eventtype)   |  - |





**Returns:** `number`





___

<a id="removelistener"></a>

###  removeListener

► **removeListener**(eventType: *[EventType](../modules/_api_.md#eventtype)*, callback: *[EventCallback](../modules/_api_.md#eventcallback)*, context?: *`any`*): `boolean`




*Inherited from [Api](_api_.api.md).[removeListener](_api_.api.md#removelistener)*

*Overrides [EventEmitter](_eventemitter_.eventemitter.md).[removeListener](_eventemitter_.eventemitter.md#removelistener)*

*Defined in [Api.ts:105](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L105)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| eventType | [EventType](../modules/_api_.md#eventtype)   |  - |
| callback | [EventCallback](../modules/_api_.md#eventcallback)   |  - |
| context | `any`   |  - |





**Returns:** `boolean`





___

<a id="scanqrcode"></a>

###  scanQRCode

► **scanQRCode**(needResult: *`boolean`*, callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[QRCodeResponse](../interfaces/_protocol_.qrcoderesponse.md)*): `void`

► **scanQRCode**(callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[QRCodeResponse](../interfaces/_protocol_.qrcoderesponse.md)*): `void`

► **scanQRCode**(needResult?: *`undefined`⎮`true`⎮`false`*): `Promise`.<[QRCodeResponse](../interfaces/_protocol_.qrcoderesponse.md)>




*Inherited from [Api](_api_.api.md).[scanQRCode](_api_.api.md#scanqrcode)*

*Defined in [Api.ts:542](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L542)*



扫二维码
*__platform__*: `Android` | `IOS`

*__alias__*: QRcode



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| needResult | `boolean`   |  指定是否返回结果 |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[QRCodeResponse](../interfaces/_protocol_.qrcoderesponse.md)   |  - |





**Returns:** `void`




*Inherited from [Api](_api_.api.md).[scanQRCode](_api_.api.md#scanqrcode)*

*Defined in [Api.ts:546](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L546)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[QRCodeResponse](../interfaces/_protocol_.qrcoderesponse.md)   |  - |





**Returns:** `void`




*Inherited from [Api](_api_.api.md).[scanQRCode](_api_.api.md#scanqrcode)*

*Defined in [Api.ts:547](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L547)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| needResult | `undefined`⎮`true`⎮`false`   |  - |





**Returns:** `Promise`.<[QRCodeResponse](../interfaces/_protocol_.qrcoderesponse.md)>





___

<a id="selectcontact"></a>

###  selectContact

► **selectContact**(params: *[SelectContactParams](../interfaces/_protocol_.selectcontactparams.md)*, callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[SelectContactResponse](../modules/_protocol_.md#selectcontactresponse)*): `void`

► **selectContact**(params: *[SelectContactParams](../interfaces/_protocol_.selectcontactparams.md)*): `Promise`.<[SelectContactResponse](../modules/_protocol_.md#selectcontactresponse)>




*Inherited from [Api](_api_.api.md).[selectContact](_api_.api.md#selectcontact)*

*Defined in [Api.ts:253](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L253)*



通讯录(联系人)选择器  
FIXME: 没有错误处理
*__platform__*: `Windows` | `Android` | `IOS`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| params | [SelectContactParams](../interfaces/_protocol_.selectcontactparams.md)   |  - |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[SelectContactResponse](../modules/_protocol_.md#selectcontactresponse)   |  - |





**Returns:** `void`




*Inherited from [Api](_api_.api.md).[selectContact](_api_.api.md#selectcontact)*

*Defined in [Api.ts:257](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L257)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| params | [SelectContactParams](../interfaces/_protocol_.selectcontactparams.md)   |  - |





**Returns:** `Promise`.<[SelectContactResponse](../modules/_protocol_.md#selectcontactresponse)>





___

<a id="selectsession"></a>

###  selectSession

► **selectSession**(params: *[SelectSessionParams](../interfaces/_protocol_.selectsessionparams.md)*, callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[SelectSessionResponseOld](../interfaces/_protocol_.selectsessionresponseold.md)*): `void`

► **selectSession**(callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[SelectSessionResponseOld](../interfaces/_protocol_.selectsessionresponseold.md)*): `void`

► **selectSession**(params?: *[SelectSessionParams](../interfaces/_protocol_.selectsessionparams.md)*): `Promise`.<[SelectSessionResponse](../modules/_protocol_.md#selectsessionresponse)>




*Inherited from [Api](_api_.api.md).[selectSession](_api_.api.md#selectsession)*

*Defined in [Api.ts:696](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L696)*



用户获取会话id
*__platform__*: *



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| params | [SelectSessionParams](../interfaces/_protocol_.selectsessionparams.md)   |  参数  + `multiple`: 表示支持多选  + `title`: 设置对话框的标题 |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[SelectSessionResponseOld](../interfaces/_protocol_.selectsessionresponseold.md)   |  回调函数 |





**Returns:** `void`




*Inherited from [Api](_api_.api.md).[selectSession](_api_.api.md#selectsession)*

*Defined in [Api.ts:700](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L700)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[SelectSessionResponseOld](../interfaces/_protocol_.selectsessionresponseold.md)   |  - |





**Returns:** `void`




*Inherited from [Api](_api_.api.md).[selectSession](_api_.api.md#selectsession)*

*Defined in [Api.ts:701](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L701)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| params | [SelectSessionParams](../interfaces/_protocol_.selectsessionparams.md)   |  - |





**Returns:** `Promise`.<[SelectSessionResponse](../modules/_protocol_.md#selectsessionresponse)>





___

<a id="setbackbuttonvisible"></a>

###  setBackButtonVisible

► **setBackButtonVisible**(visible?: *`boolean`*): `void`




*Defined in [MobileApi.ts:70](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L70)*



设置返回按钮的可见性

> 关闭按钮和返回按钮只能隐藏一个


**Parameters:**

| Param | Type | Default value | Description |
| ------ | ------ | ------ | ------ |
| visible | `boolean`  | true |   - |





**Returns:** `void`





___

<a id="setbarbuttonvisible"></a>

### «Private» setBarButtonVisible

► **setBarButtonVisible**(visible: *`boolean`*, name: *`string`*): `void`




*Defined in [MobileApi.ts:110](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L110)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| visible | `boolean`   |  - |
| name | `string`   |  - |





**Returns:** `void`





___

<a id="setbarcolor"></a>

###  setBarColor

► **setBarColor**(color: *`string`*): `void`




*Inherited from [Api](_api_.api.md).[setBarColor](_api_.api.md#setbarcolor)*

*Defined in [Api.ts:296](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L296)*



设置Bar颜色

> 注意：目前只支持`RGB hex`格式的颜色值， 如`#FFFFFF`
*__platform__*: `Android` | `IOS`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| color | `string`   |  颜色值 |





**Returns:** `void`





___

<a id="setbarvisible"></a>

###  setBarVisible

► **setBarVisible**(visible: *`boolean`*): `void`




*Inherited from [Api](_api_.api.md).[setBarVisible](_api_.api.md#setbarvisible)*

*Defined in [Api.ts:309](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L309)*



设置Bar的显示和隐藏, 也可以使用`showBar`显示， `hideBar` 隐藏
*__platform__*: `Android` | `IOS`

*__see__*: showBar

*__see__*: hideBar



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| visible | `boolean`   |  - |





**Returns:** `void`





___

<a id="setclosebuttonvisible"></a>

###  setCloseButtonVisible

► **setCloseButtonVisible**(visible?: *`boolean`*): `void`




*Defined in [MobileApi.ts:78](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L78)*



设置关闭按钮的可见性

> 关闭按钮和返回按钮只能隐藏一个


**Parameters:**

| Param | Type | Default value | Description |
| ------ | ------ | ------ | ------ |
| visible | `boolean`  | true |   - |





**Returns:** `void`





___

<a id="setmorebuttonvisible"></a>

###  setMoreButtonVisible

► **setMoreButtonVisible**(visible?: *`boolean`*): `void`




*Defined in [MobileApi.ts:61](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L61)*



设置'更多'的可见性


**Parameters:**

| Param | Type | Default value | Description |
| ------ | ------ | ------ | ------ |
| visible | `boolean`  | true |   - |





**Returns:** `void`





___

<a id="settitle"></a>

###  setTitle

► **setTitle**(title: *`string`*): `void`




*Inherited from [Api](_api_.api.md).[setTitle](_api_.api.md#settitle)*

*Defined in [Api.ts:129](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L129)*



设置标题
*__platform__*: `Windows` | `Android` | `IOS` | `Web`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| title | `string`   |  - |





**Returns:** `void`





___

<a id="setupbeforeunloadwatcher"></a>

### «Private» setUpBeforeUnloadWatcher

► **setUpBeforeUnloadWatcher**(callback: *function*): `void`




*Defined in [MobileApi.ts:204](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L204)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callback | function   |  - |





**Returns:** `void`





___

<a id="setupbridge"></a>

###  setUpBridge

► **setUpBridge**(callback: *function*): `void`




*Overrides [Api](_api_.api.md).[setUpBridge](_api_.api.md#setupbridge)*

*Defined in [MobileApi.ts:106](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L106)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callback | function   |  - |





**Returns:** `void`





___

<a id="setupgobackwatcher"></a>

### «Private» setUpGobackWatcher

► **setUpGobackWatcher**(callback: *function*): `void`




*Defined in [MobileApi.ts:209](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L209)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callback | function   |  - |





**Returns:** `void`





___

<a id="settingbar"></a>

###  settingBar

► **settingBar**(params: *`Partial`.<[SetBarParams](../interfaces/_protocol_.setbarparams.md)>*, callback: *[LegacyCallback](../modules/_protocol_.md#legacycallback)[SetBarResponseOld](../interfaces/_protocol_.setbarresponseold.md)*): `void`




*Inherited from [Api](_api_.api.md).[settingBar](_api_.api.md#settingbar)*

*Defined in [Api.ts:340](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L340)*



设置状态栏，并监听事件
*__platform__*: `Android` | `IOS`

*__deprecated__*: 



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| params | `Partial`.<[SetBarParams](../interfaces/_protocol_.setbarparams.md)>   |  - |
| callback | [LegacyCallback](../modules/_protocol_.md#legacycallback)[SetBarResponseOld](../interfaces/_protocol_.setbarresponseold.md)   |  - |





**Returns:** `void`





___

<a id="setupbarwatcher"></a>

### «Private» setupBarWatcher

► **setupBarWatcher**(): `void`




*Defined in [MobileApi.ts:139](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L139)*





**Returns:** `void`





___

<a id="setupeventwatcher"></a>

### «Protected» setupEventWatcher

► **setupEventWatcher**(eventName: *`string`*, callback: *function*): `void`




*Overrides [Api](_api_.api.md).[setupEventWatcher](_api_.api.md#setupeventwatcher)*

*Defined in [MobileApi.ts:82](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L82)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| eventName | `string`   |  - |
| callback | function   |  - |





**Returns:** `void`





___

<a id="shareto"></a>

###  shareTo

► **shareTo**(): `void`




*Inherited from [Api](_api_.api.md).[shareTo](_api_.api.md#shareto)*

*Defined in [Api.ts:600](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L600)*



分享
*__platform__*: `Android` | `IOS` TODO: 可以改进， 允许自定义分享内容





**Returns:** `void`





___

<a id="showbar"></a>

###  showBar

► **showBar**(flag?: *`undefined`⎮`true`⎮`false`*): `void`




*Inherited from [Api](_api_.api.md).[showBar](_api_.api.md#showbar)*

*Defined in [Api.ts:320](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L320)*



显示Bar
*__platform__*: `Android` | `IOS`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| flag | `undefined`⎮`true`⎮`false`   |  已废弃，兼容旧版本接口 |





**Returns:** `void`





___

<a id="showcontact"></a>

###  showContact

► **showContact**(id: *`string`*): `void`




*Inherited from [Api](_api_.api.md).[showContact](_api_.api.md#showcontact)*

*Defined in [Api.ts:229](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L229)*



打开名片
*__platform__*: `Windows` | `Android` | `IOS`

*__alias__*: openContact



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| id | `string`   |  用户id |





**Returns:** `void`





___

<a id="sms"></a>

###  sms

► **sms**(callNumber: *`string`*): `void`




*Inherited from [Api](_api_.api.md).[sms](_api_.api.md#sms)*

*Defined in [Api.ts:157](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L157)*



发送消息
*__platform__*: `Android` | `IOS`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| callNumber | `string`   |  手机号码 |





**Returns:** `void`





___

<a id="teardown"></a>

###  teardown

► **teardown**(): `void`




*Inherited from [Api](_api_.api.md).[teardown](_api_.api.md#teardown)*

*Defined in [Api.ts:792](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L792)*





**Returns:** `void`





___

<a id="teardowneventwatcher"></a>

### «Protected» teardownEventWatcher

► **teardownEventWatcher**(eventName: *`string`*): `void`




*Overrides [Api](_api_.api.md).[teardownEventWatcher](_api_.api.md#teardowneventwatcher)*

*Defined in [MobileApi.ts:95](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L95)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| eventName | `string`   |  - |





**Returns:** `void`





___

<a id="url"></a>

###  url

► **url**(params: *[LocationToParams](../interfaces/_protocol_.locationtoparams.md)*): `void`




*Inherited from [Api](_api_.api.md).[url](_api_.api.md#url)*

*Defined in [Api.ts:215](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/Api.ts#L215)*



打开指定链接
*__platform__*: `Windows` | `Android` | `IOS` | `Web`

*__alias__*: locationTo

*__deprecated__*: 使用locationTo代替



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| params | [LocationToParams](../interfaces/_protocol_.locationtoparams.md)   |  - |





**Returns:** `void`





___

<a id="watchlistener"></a>

### «Private» watchListener

► **watchListener**(eventName: *`string`*): `void`




*Defined in [MobileApi.ts:181](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L181)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| eventName | `string`   |  - |





**Returns:** `void`





___

<a id="getinstance"></a>

### «Static» getInstance

► **getInstance**(): [Api](_api_.api.md)




*Defined in [MobileApi.ts:39](https://github.com/GDJiaMi/gzb-jssdk/blob/6a995d9/src/MobileApi.ts#L39)*





**Returns:** [Api](_api_.api.md)





___



