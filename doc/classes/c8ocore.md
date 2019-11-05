[c8osdkjscore](../README.md) › [C8oCore](c8ocore.md)

# Class: C8oCore

Allows to send requests to a Convertigo Server (or Studio), these requests are called c8o calls.<br/>
C8o calls are done thanks to a HTTP request or a CouchbaseLite usage.<br/>
An instance of C8o is connected to only one Convertigo and can't change it.<br/>
To use it, you have to first initialize the C8o instance with the Convertigo endpoint, then use call methods with Convertigo variables as parameter.

## Hierarchy

* [C8oBase](c8obase.md)

  ↳ **C8oCore**

  ↳ [C8o](c8o.md)

## Index

### Constructors

* [constructor](c8ocore.md#constructor)

### Properties

* [_authenticationCookieValue](c8ocore.md#protected-_authenticationcookievalue)
* [_automaticRemoveSplashsCreen](c8ocore.md#protected-_automaticremovesplashscreen)
* [_clientCertificateBinaries](c8ocore.md#protected-_clientcertificatebinaries)
* [_clientCertificateFiles](c8ocore.md#protected-_clientcertificatefiles)
* [_cookies](c8ocore.md#protected-_cookies)
* [_couchUrl](c8ocore.md#protected-_couchurl)
* [_defaultDatabaseName](c8ocore.md#protected-_defaultdatabasename)
* [_disableSSL](c8ocore.md#protected-_disablessl)
* [_endpoint](c8ocore.md#protected-_endpoint)
* [_endpointConvertigo](c8ocore.md#protected-_endpointconvertigo)
* [_endpointHost](c8ocore.md#protected-_endpointhost)
* [_endpointIsSecure](c8ocore.md#protected-_endpointissecure)
* [_endpointPort](c8ocore.md#protected-_endpointport)
* [_endpointProject](c8ocore.md#protected-_endpointproject)
* [_endpointSettings](c8ocore.md#protected-_endpointsettings)
* [_errorConvertigoIntoFail](c8ocore.md#protected-_errorconvertigointofail)
* [_fullSyncLocalSuffix](c8ocore.md#protected-_fullsynclocalsuffix)
* [_fullSyncPassword](c8ocore.md#protected-_fullsyncpassword)
* [_fullSyncServerUrl](c8ocore.md#protected-_fullsyncserverurl)
* [_fullSyncUsername](c8ocore.md#protected-_fullsyncusername)
* [_headers](c8ocore.md#protected-_headers)
* [_http](c8ocore.md#protected-_http)
* [_initalLogLevel](c8ocore.md#protected-_initalloglevel)
* [_initialLogRemote](c8ocore.md#protected-_initiallogremote)
* [_keepSessionAlive](c8ocore.md#protected-_keepsessionalive)
* [_keyStorePassword](c8ocore.md#protected-_keystorepassword)
* [_logC8o](c8ocore.md#protected-_logc8o)
* [_logLevelLocal](c8ocore.md#protected-_loglevellocal)
* [_logOnFail](c8ocore.md#protected-_logonfail)
* [_logRemote](c8ocore.md#protected-_logremote)
* [_normalizeParameters](c8ocore.md#protected-_normalizeparameters)
* [_prefixBase](c8ocore.md#protected-_prefixbase)
* [_reply](c8ocore.md#private-_reply)
* [_resetBase](c8ocore.md#protected-_resetbase)
* [_timeout](c8ocore.md#protected-_timeout)
* [_trustStorePassword](c8ocore.md#protected-_truststorepassword)
* [_useEncryption](c8ocore.md#protected-_useencryption)
* [_waitingForInit](c8ocore.md#private-_waitingforinit)
* [c8oFullSync](c8ocore.md#c8ofullsync)
* [c8oLogger](c8ocore.md#c8ologger)
* [data](c8ocore.md#protected-data)
* [database](c8ocore.md#database)
* [handleFullSyncLive](c8ocore.md#protected-handlefullsynclive)
* [httpInterface](c8ocore.md#httpinterface)
* [lives](c8ocore.md#lives)
* [livesDb](c8ocore.md#livesdb)
* [network](c8ocore.md#network)
* [promiseConstructor](c8ocore.md#protected-promiseconstructor)
* [promiseFinInit](c8ocore.md#promisefininit)
* [promiseInit](c8ocore.md#protected-promiseinit)
* [promiseManagerNetwork](c8ocore.md#private-promisemanagernetwork)
* [promiseReachable](c8ocore.md#protected-promisereachable)
* [reachable](c8ocore.md#reachable)
* [replicationsToRestart](c8ocore.md#protected-replicationstorestart)
* [session](c8ocore.md#session)
* [subscriber_login](c8ocore.md#subscriber_login)
* [subscriber_network](c8ocore.md#subscriber_network)
* [subscriber_session](c8ocore.md#subscriber_session)
* [ENGINE_PARAMETER_CONNECTOR](c8ocore.md#static-engine_parameter_connector)
* [ENGINE_PARAMETER_DEVICE_UUID](c8ocore.md#static-engine_parameter_device_uuid)
* [ENGINE_PARAMETER_ENCODED](c8ocore.md#static-engine_parameter_encoded)
* [ENGINE_PARAMETER_FROM_LIVE](c8ocore.md#static-engine_parameter_from_live)
* [ENGINE_PARAMETER_PROGRESS](c8ocore.md#static-engine_parameter_progress)
* [ENGINE_PARAMETER_PROJECT](c8ocore.md#static-engine_parameter_project)
* [ENGINE_PARAMETER_SEQUENCE](c8ocore.md#static-engine_parameter_sequence)
* [ENGINE_PARAMETER_TRANSACTION](c8ocore.md#static-engine_parameter_transaction)
* [FS_LIVE](c8ocore.md#static-fs_live)
* [FS_POLICY](c8ocore.md#static-fs_policy)
* [FS_POLICY_CREATE](c8ocore.md#static-fs_policy_create)
* [FS_POLICY_MERGE](c8ocore.md#static-fs_policy_merge)
* [FS_POLICY_NONE](c8ocore.md#static-fs_policy_none)
* [FS_POLICY_OVERRIDE](c8ocore.md#static-fs_policy_override)
* [FS_SUBKEY_SEPARATOR](c8ocore.md#static-fs_subkey_separator)
* [LOCAL_CACHE_DATABASE_NAME](c8ocore.md#static-local_cache_database_name)
* [LOCAL_CACHE_DOCUMENT_KEY_EXPIRATION_DATE](c8ocore.md#static-local_cache_document_key_expiration_date)
* [LOCAL_CACHE_DOCUMENT_KEY_RESPONSE](c8ocore.md#static-local_cache_document_key_response)
* [LOCAL_CACHE_DOCUMENT_KEY_RESPONSE_TYPE](c8ocore.md#static-local_cache_document_key_response_type)
* [RESPONSE_TYPE_JSON](c8ocore.md#static-response_type_json)
* [RESPONSE_TYPE_XML](c8ocore.md#static-response_type_xml)
* [RE_ENDPOINT](c8ocore.md#static-protected-re_endpoint)
* [RE_REQUESTABLE](c8ocore.md#static-protected-re_requestable)
* [deviceUUID](c8ocore.md#static-private-deviceuuid)

### Accessors

* [authenticationCookieValue](c8ocore.md#authenticationcookievalue)
* [cookies](c8ocore.md#cookies)
* [coreVersion](c8ocore.md#coreversion)
* [couchUrl](c8ocore.md#couchurl)
* [defaultDatabaseName](c8ocore.md#defaultdatabasename)
* [deviceUUID](c8ocore.md#deviceuuid)
* [endpoint](c8ocore.md#endpoint)
* [endpointConvertigo](c8ocore.md#endpointconvertigo)
* [endpointHost](c8ocore.md#endpointhost)
* [endpointIsSecure](c8ocore.md#endpointissecure)
* [endpointPort](c8ocore.md#endpointport)
* [endpointProject](c8ocore.md#endpointproject)
* [errorConvertigoIntoFail](c8ocore.md#errorconvertigointofail)
* [fullSyncLocalSuffix](c8ocore.md#fullsynclocalsuffix)
* [fullSyncPassword](c8ocore.md#fullsyncpassword)
* [fullSyncServerUrl](c8ocore.md#fullsyncserverurl)
* [fullSyncUsername](c8ocore.md#fullsyncusername)
* [headers](c8ocore.md#headers)
* [httpPublic](c8ocore.md#httppublic)
* [keepSessionAlive](c8ocore.md#keepsessionalive)
* [log](c8ocore.md#log)
* [logC8o](c8ocore.md#logc8o)
* [logLevelLocal](c8ocore.md#loglevellocal)
* [logOnFail](c8ocore.md#logonfail)
* [logRemote](c8ocore.md#logremote)
* [normalizeParameters](c8ocore.md#normalizeparameters)
* [prefixBase](c8ocore.md#prefixbase)
* [resetBase](c8ocore.md#resetbase)
* [sdkVersion](c8ocore.md#sdkversion)
* [timeout](c8ocore.md#timeout)

### Methods

* [_call](c8ocore.md#_call)
* [addFullSyncChangeListener](c8ocore.md#addfullsyncchangelistener)
* [addLive](c8ocore.md#addlive)
* [call](c8ocore.md#call)
* [callJson](c8ocore.md#calljson)
* [callJsonObject](c8ocore.md#calljsonobject)
* [cancelLive](c8ocore.md#cancellive)
* [copy](c8ocore.md#copy)
* [extractendpoint](c8ocore.md#protected-extractendpoint)
* [finalizeInit](c8ocore.md#finalizeinit)
* [get_attachment](c8ocore.md#get_attachment)
* [handleAutoLoginResponse](c8ocore.md#handleautologinresponse)
* [handleCallException](c8ocore.md#handlecallexception)
* [handleNetworkEvents](c8ocore.md#handlenetworkevents)
* [handleSessionLost](c8ocore.md#handlesessionlost)
* [httpGetObservable](c8ocore.md#abstract-httpgetobservable)
* [init](c8ocore.md#init)
* [initC8oHttInterface](c8ocore.md#abstract-initc8ohttinterface)
* [removeFullSyncChangeListener](c8ocore.md#removefullsyncchangelistener)
* [removeNull](c8ocore.md#removenull)
* [toString](c8ocore.md#tostring)
* [toParameters](c8ocore.md#static-toparameters)

## Constructors

###  constructor

\+ **new C8oCore**(): *[C8oCore](c8ocore.md)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:328](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L328)*

This is the base object representing a Convertigo Server end point. This object should be instantiated
when the apps starts and be accessible from any class of the app. Although this is not common , you may have
several C8o objects instantiated in your app.

**`throws`** C8oException In case of invalid parameter or initialization failure.

**Returns:** *[C8oCore](c8ocore.md)*

## Properties

### `Protected` _authenticationCookieValue

• **_authenticationCookieValue**: *string* =  null

*Inherited from [C8oBase](c8obase.md).[_authenticationCookieValue](c8obase.md#protected-_authenticationcookievalue)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:21](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L21)*

___

### `Protected` _automaticRemoveSplashsCreen

• **_automaticRemoveSplashsCreen**: *boolean* = true

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:143](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L143)*

___

### `Protected` _clientCertificateBinaries

• **_clientCertificateBinaries**: *Object*

*Inherited from [C8oBase](c8obase.md).[_clientCertificateBinaries](c8obase.md#protected-_clientcertificatebinaries)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:10](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L10)*

___

### `Protected` _clientCertificateFiles

• **_clientCertificateFiles**: *Object*

*Inherited from [C8oBase](c8obase.md).[_clientCertificateFiles](c8obase.md#protected-_clientcertificatefiles)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:9](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L9)*

___

### `Protected` _cookies

• **_cookies**: *Object*

*Inherited from [C8oBase](c8obase.md).[_cookies](c8obase.md#protected-_cookies)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:8](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L8)*

___

### `Protected` _couchUrl

• **_couchUrl**: *string* =  null

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:171](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L171)*

___

### `Protected` _defaultDatabaseName

• **_defaultDatabaseName**: *string* =  null

*Inherited from [C8oBase](c8obase.md).[_defaultDatabaseName](c8obase.md#protected-_defaultdatabasename)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:20](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L20)*

___

### `Protected` _disableSSL

• **_disableSSL**: *boolean* = false

*Inherited from [C8oBase](c8obase.md).[_disableSSL](c8obase.md#protected-_disablessl)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:29](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L29)*

___

### `Protected` _endpoint

• **_endpoint**: *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:137](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L137)*

The Convertigo endpoint, syntax: &lt;protocol&gt;://&lt;host&gt;:&lt;port&gt;/&lt;Convertigo web app path&gt;/projects/&lt;project name&gt; (Example: http://127.0.0.1:18080/convertigo/projects/MyProject)

___

### `Protected` _endpointConvertigo

• **_endpointConvertigo**: *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:138](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L138)*

___

### `Protected` _endpointHost

• **_endpointHost**: *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:140](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L140)*

___

### `Protected` _endpointIsSecure

• **_endpointIsSecure**: *boolean*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:139](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L139)*

___

### `Protected` _endpointPort

• **_endpointPort**: *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:141](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L141)*

___

### `Protected` _endpointProject

• **_endpointProject**: *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:142](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L142)*

___

### `Protected` _endpointSettings

• **_endpointSettings**: *string*

*Inherited from [C8oBase](c8obase.md).[_endpointSettings](c8obase.md#protected-_endpointsettings)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:5](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L5)*

___

### `Protected` _errorConvertigoIntoFail

• **_errorConvertigoIntoFail**: *boolean* = false

*Inherited from [C8oBase](c8obase.md).[_errorConvertigoIntoFail](c8obase.md#protected-_errorconvertigointofail)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:40](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L40)*

___

### `Protected` _fullSyncLocalSuffix

• **_fullSyncLocalSuffix**: *string* =  null

*Inherited from [C8oBase](c8obase.md).[_fullSyncLocalSuffix](c8obase.md#protected-_fullsynclocalsuffix)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:22](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L22)*

___

### `Protected` _fullSyncPassword

• **_fullSyncPassword**: *string*

*Inherited from [C8oBase](c8obase.md).[_fullSyncPassword](c8obase.md#protected-_fullsyncpassword)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:25](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L25)*

___

### `Protected` _fullSyncServerUrl

• **_fullSyncServerUrl**: *string* = "http://localhost:5984"

*Inherited from [C8oBase](c8obase.md).[_fullSyncServerUrl](c8obase.md#protected-_fullsyncserverurl)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:23](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L23)*

___

### `Protected` _fullSyncUsername

• **_fullSyncUsername**: *string*

*Inherited from [C8oBase](c8obase.md).[_fullSyncUsername](c8obase.md#protected-_fullsyncusername)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:24](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L24)*

___

### `Protected` _headers

• **_headers**: *Object*

*Inherited from [C8oBase](c8obase.md).[_headers](c8obase.md#protected-_headers)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:46](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L46)*

___

### `Protected` _http

• **_http**: *any*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:170](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L170)*

___

### `Protected` _initalLogLevel

• **_initalLogLevel**: *Boolean*

*Inherited from [C8oBase](c8obase.md).[_initalLogLevel](c8obase.md#protected-_initalloglevel)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:48](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L48)*

___

### `Protected` _initialLogRemote

• **_initialLogRemote**: *boolean* = true

*Inherited from [C8oBase](c8obase.md).[_initialLogRemote](c8obase.md#protected-_initiallogremote)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:14](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L14)*

___

### `Protected` _keepSessionAlive

• **_keepSessionAlive**: *boolean* = true

*Inherited from [C8oBase](c8obase.md).[_keepSessionAlive](c8obase.md#protected-_keepsessionalive)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:38](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L38)*

___

### `Protected` _keyStorePassword

• **_keyStorePassword**: *string*

*Inherited from [C8oBase](c8obase.md).[_keyStorePassword](c8obase.md#protected-_keystorepassword)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:31](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L31)*

___

### `Protected` _logC8o

• **_logC8o**: *boolean* = false

*Inherited from [C8oBase](c8obase.md).[_logC8o](c8obase.md#protected-_logc8o)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:16](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L16)*

___

### `Protected` _logLevelLocal

• **_logLevelLocal**: *[C8oLogLevel](c8ologlevel.md)* =  C8oLogLevel.NONE

*Inherited from [C8oBase](c8obase.md).[_logLevelLocal](c8obase.md#protected-_loglevellocal)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:15](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L15)*

___

### `Protected` _logOnFail

• **_logOnFail**: *function*

*Inherited from [C8oBase](c8obase.md).[_logOnFail](c8obase.md#protected-_logonfail)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:17](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L17)*

#### Type declaration:

▸ (`exception`: Error, `parameters`: Object): *void*

**Parameters:**

Name | Type |
------ | ------ |
`exception` | Error |
`parameters` | Object |

___

### `Protected` _logRemote

• **_logRemote**: *boolean* = true

*Inherited from [C8oBase](c8obase.md).[_logRemote](c8obase.md#protected-_logremote)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:13](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L13)*

___

### `Protected` _normalizeParameters

• **_normalizeParameters**: *boolean*

*Inherited from [C8oBase](c8obase.md).[_normalizeParameters](c8obase.md#protected-_normalizeparameters)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:36](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L36)*

___

### `Protected` _prefixBase

• **_prefixBase**: *boolean* = false

*Inherited from [C8oBase](c8obase.md).[_prefixBase](c8obase.md#protected-_prefixbase)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:44](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L44)*

___

### `Private` _reply

• **_reply**: *Subject‹any›* =  new Subject<any>()

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:167](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L167)*

___

### `Protected` _resetBase

• **_resetBase**: *boolean* = true

*Inherited from [C8oBase](c8obase.md).[_resetBase](c8obase.md#protected-_resetbase)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:42](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L42)*

___

### `Protected` _timeout

• **_timeout**: *number* =  -1

*Inherited from [C8oBase](c8obase.md).[_timeout](c8obase.md#protected-_timeout)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:6](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L6)*

___

### `Protected` _trustStorePassword

• **_trustStorePassword**: *string*

*Inherited from [C8oBase](c8obase.md).[_trustStorePassword](c8obase.md#protected-_truststorepassword)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:33](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L33)*

___

### `Protected` _useEncryption

• **_useEncryption**: *boolean* = false

*Inherited from [C8oBase](c8obase.md).[_useEncryption](c8obase.md#protected-_useencryption)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:28](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L28)*

___

### `Private` _waitingForInit

• **_waitingForInit**: *any*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:178](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L178)*

___

###  c8oFullSync

• **c8oFullSync**: *[C8oFullSync](c8ofullsync.md)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:158](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L158)*

Used to run fullSync requests.

___

###  c8oLogger

• **c8oLogger**: *[C8oLogger](c8ologger.md)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:153](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L153)*

Allows to log locally and remotely to the Convertigo server.

___

### `Protected` data

• **data**: *any*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:169](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L169)*

___

###  database

• **database**: *[C8oManagerDatabase](c8omanagerdatabase.md)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:182](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L182)*

___

### `Protected` handleFullSyncLive

• **handleFullSyncLive**: *[C8oFullSyncChangeListener](c8ofullsyncchangelistener.md)* =  new C8oFullSyncChangeListener(
        (changes: Object) => {
            for (const task in this.lives) {
                (this.lives[task] as C8oCallTask).executeFromLive();
            }
    })

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:638](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L638)*

___

###  httpInterface

• **httpInterface**: *[C8oHttpInterfaceCore](c8ohttpinterfacecore.md)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:148](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L148)*

Used to run HTTP requests.

___

###  lives

• **lives**: *[C8oCallTask](c8ocalltask.md)[]* =  []

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:160](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L160)*

___

###  livesDb

• **livesDb**: *string[]* =  []

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:161](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L161)*

___

###  network

• **network**: *[C8oManagerNetwork](c8omanagernetwork.md)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:181](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L181)*

___

### `Protected` promiseConstructor

• **promiseConstructor**: *Promise‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:172](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L172)*

___

###  promiseFinInit

• **promiseFinInit**: *Promise‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:174](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L174)*

___

### `Protected` promiseInit

• **promiseInit**: *Promise‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:173](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L173)*

___

### `Private` promiseManagerNetwork

• **promiseManagerNetwork**: *Promise‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:176](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L176)*

___

### `Protected` promiseReachable

• **promiseReachable**: *Promise‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:175](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L175)*

___

###  reachable

• **reachable**: *any*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:179](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L179)*

___

### `Protected` replicationsToRestart

• **replicationsToRestart**: *Array‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:177](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L177)*

___

###  session

• **session**: *[C8oManagerSession](c8omanagersession.md)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:183](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L183)*

___

###  subscriber_login

• **subscriber_login**: *Subject‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:165](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L165)*

___

###  subscriber_network

• **subscriber_network**: *Subject‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:164](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L164)*

___

###  subscriber_session

• **subscriber_session**: *Subject‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:163](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L163)*

___

### `Static` ENGINE_PARAMETER_CONNECTOR

▪ **ENGINE_PARAMETER_CONNECTOR**: *string* = "__connector"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:57](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L57)*

___

### `Static` ENGINE_PARAMETER_DEVICE_UUID

▪ **ENGINE_PARAMETER_DEVICE_UUID**: *string* = "__uuid"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:60](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L60)*

___

### `Static` ENGINE_PARAMETER_ENCODED

▪ **ENGINE_PARAMETER_ENCODED**: *string* = "__encoded"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:59](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L59)*

___

### `Static` ENGINE_PARAMETER_FROM_LIVE

▪ **ENGINE_PARAMETER_FROM_LIVE**: *string* = "__fromLive"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:62](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L62)*

___

### `Static` ENGINE_PARAMETER_PROGRESS

▪ **ENGINE_PARAMETER_PROGRESS**: *string* = "__progress"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:61](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L61)*

___

### `Static` ENGINE_PARAMETER_PROJECT

▪ **ENGINE_PARAMETER_PROJECT**: *string* = "__project"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:55](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L55)*

 Engine reserved parameters

___

### `Static` ENGINE_PARAMETER_SEQUENCE

▪ **ENGINE_PARAMETER_SEQUENCE**: *string* = "__sequence"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:56](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L56)*

___

### `Static` ENGINE_PARAMETER_TRANSACTION

▪ **ENGINE_PARAMETER_TRANSACTION**: *string* = "__transaction"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:58](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L58)*

___

### `Static` FS_LIVE

▪ **FS_LIVE**: *string* = "__live"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:116](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L116)*

Use it with "fs://" request as parameter to enable the live request feature.<br/>
Must be followed by a string parameter, the 'liveid' that can be use to cancel the live
request using c8o.cancelLive(liveid) method.<br/>
A live request automatically recall the then or thenUI handler when the database changed.

___

### `Static` FS_POLICY

▪ **FS_POLICY**: *string* = "_use_policy"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:78](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L78)*

Constant to use as a parameter for a Call of "fs://.post" and must be followed by a FS_POLICY_* constant.
<pre>{@code
c8o.callJson("fs://.post",
  C8o.FS_POLICY, C8o.FS_POLICY_MERGE,
  "docid", myid,
  "mykey", myvalue
).sync();
}</pre>

___

### `Static` FS_POLICY_CREATE

▪ **FS_POLICY_CREATE**: *string* = "create"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:90](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L90)*

Use it with "fs://.post" and C8o.FS_POLICY.

This post policy remove the "_id" and "_rev" of the document before the CouchbaseLite's insertion.

___

### `Static` FS_POLICY_MERGE

▪ **FS_POLICY_MERGE**: *string* = "merge"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:102](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L102)*

Use it with "fs://.post" and C8o.FS_POLICY.

This post policy merge the document with an existing document with the same "_id" before the CouchbaseLite's insertion.

___

### `Static` FS_POLICY_NONE

▪ **FS_POLICY_NONE**: *string* = "none"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:84](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L84)*

Use it with "fs://.post" and C8o.FS_POLICY.

This is the default post policy that don't alter the document before the CouchbaseLite's insertion.

___

### `Static` FS_POLICY_OVERRIDE

▪ **FS_POLICY_OVERRIDE**: *string* = "override"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:96](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L96)*

Use it with "fs://.post" and C8o.FS_POLICY.

This post policy inserts the document in CouchbaseLite even if a document with the same "_id" already exists.

___

### `Static` FS_SUBKEY_SEPARATOR

▪ **FS_SUBKEY_SEPARATOR**: *string* = "_use_subkey_separator"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:108](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L108)*

Use it with "fs://.post". Default value is ".".

This key allow to override the sub key separator in case of document depth modification.

___

### `Static` LOCAL_CACHE_DATABASE_NAME

▪ **LOCAL_CACHE_DATABASE_NAME**: *string* = "c8olocalcache"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:123](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L123)*

___

### `Static` LOCAL_CACHE_DOCUMENT_KEY_EXPIRATION_DATE

▪ **LOCAL_CACHE_DOCUMENT_KEY_EXPIRATION_DATE**: *string* = "expirationDate"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:121](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L121)*

___

### `Static` LOCAL_CACHE_DOCUMENT_KEY_RESPONSE

▪ **LOCAL_CACHE_DOCUMENT_KEY_RESPONSE**: *string* = "response"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:119](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L119)*

Local cache keys

___

### `Static` LOCAL_CACHE_DOCUMENT_KEY_RESPONSE_TYPE

▪ **LOCAL_CACHE_DOCUMENT_KEY_RESPONSE_TYPE**: *string* = "responseType"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:120](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L120)*

___

### `Static` RESPONSE_TYPE_JSON

▪ **RESPONSE_TYPE_JSON**: *string* = "json"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:127](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L127)*

___

### `Static` RESPONSE_TYPE_XML

▪ **RESPONSE_TYPE_XML**: *string* = "pxml"

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:126](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L126)*

Response type

___

### `Static` `Protected` RE_ENDPOINT

▪ **RE_ENDPOINT**: *RegExp* =  /^(https?:\/\/([^:/]+)(:[0-9]+)?\/?.*?)\/projects\/([^\/]+)$/

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:50](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L50)*

The regex used to get the part of the endpoint before '/projects/...'

___

### `Static` `Protected` RE_REQUESTABLE

▪ **RE_REQUESTABLE**: *RegExp* =  /^([^.]*)\.(?:([^.]+)|(?:([^.]+)\.([^.]+)))$/

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:45](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L45)*

The regex used to handle the c8o requestable syntax ("&lt;project&gt;.&lt;sequence&gt;" or "&lt;project&gt;.&lt;connector&gt;.&lt;transaction&gt;")

___

### `Static` `Private` deviceUUID

▪ **deviceUUID**: *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:130](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L130)*

## Accessors

###  authenticationCookieValue

• **get authenticationCookieValue**(): *string*

*Inherited from [C8oBase](c8obase.md).[authenticationCookieValue](c8obase.md#authenticationcookievalue)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:149](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L149)*

**Returns:** *string*

___

###  cookies

• **get cookies**(): *Object*

*Inherited from [C8oBase](c8obase.md).[cookies](c8obase.md#cookies)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:119](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L119)*

Gets initial cookies to send to the Convertigo server.<br/>
Default is <b>null</b>.

**Returns:** *Object*

List of cookies.

___

###  coreVersion

• **get coreVersion**(): *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:326](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L326)*

**Returns:** *string*

___

###  couchUrl

• **get couchUrl**(): *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:185](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L185)*

**Returns:** *string*

• **set couchUrl**(`value`: string): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:189](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L189)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | string |

**Returns:** *void*

___

###  defaultDatabaseName

• **get defaultDatabaseName**(): *string*

*Inherited from [C8oBase](c8obase.md).[defaultDatabaseName](c8obase.md#defaultdatabasename)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:145](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L145)*

**Returns:** *string*

___

###  deviceUUID

• **get deviceUUID**(): *Promise‹string›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:277](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L277)*

**Returns:** *Promise‹string›*

___

###  endpoint

• **get endpoint**(): *string*

*Overrides [C8oBase](c8obase.md).[endpoint](c8obase.md#endpoint)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:226](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L226)*

**Returns:** *string*

• **set endpoint**(`value`: string): *void*

*Overrides [C8oBase](c8obase.md).[endpoint](c8obase.md#endpoint)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:230](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L230)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | string |

**Returns:** *void*

___

###  endpointConvertigo

• **get endpointConvertigo**(): *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:234](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L234)*

**Returns:** *string*

• **set endpointConvertigo**(`value`: string): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:238](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L238)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | string |

**Returns:** *void*

___

###  endpointHost

• **get endpointHost**(): *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:252](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L252)*

**Returns:** *string*

• **set endpointHost**(`value`: string): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:256](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L256)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | string |

**Returns:** *void*

___

###  endpointIsSecure

• **get endpointIsSecure**(): *boolean*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:243](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L243)*

**Returns:** *boolean*

• **set endpointIsSecure**(`value`: boolean): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:247](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L247)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | boolean |

**Returns:** *void*

___

###  endpointPort

• **get endpointPort**(): *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:261](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L261)*

**Returns:** *string*

• **set endpointPort**(`value`: string): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:265](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L265)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | string |

**Returns:** *void*

___

###  endpointProject

• **get endpointProject**(): *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:269](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L269)*

**Returns:** *string*

• **set endpointProject**(`value`: string): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:273](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L273)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | string |

**Returns:** *void*

___

###  errorConvertigoIntoFail

• **get errorConvertigoIntoFail**(): *boolean*

*Inherited from [C8oBase](c8obase.md).[errorConvertigoIntoFail](c8obase.md#errorconvertigointofail)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:73](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L73)*

Gets if error convertigo are thrown into fail.<br/>
Default is <b>false</b>.

**Returns:** *boolean*

The errorConvertigoIntoFail status.

___

###  fullSyncLocalSuffix

• **get fullSyncLocalSuffix**(): *string*

*Inherited from [C8oBase](c8obase.md).[fullSyncLocalSuffix](c8obase.md#fullsynclocalsuffix)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:153](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L153)*

**Returns:** *string*

___

###  fullSyncPassword

• **get fullSyncPassword**(): *string*

*Inherited from [C8oBase](c8obase.md).[fullSyncPassword](c8obase.md#fullsyncpassword)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:168](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L168)*

**Returns:** *string*

___

###  fullSyncServerUrl

• **get fullSyncServerUrl**(): *string*

*Inherited from [C8oBase](c8obase.md).[fullSyncServerUrl](c8obase.md#fullsyncserverurl)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:158](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L158)*

**Returns:** *string*

___

###  fullSyncUsername

• **get fullSyncUsername**(): *string*

*Inherited from [C8oBase](c8obase.md).[fullSyncUsername](c8obase.md#fullsyncusername)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:163](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L163)*

**Returns:** *string*

___

###  headers

• **get headers**(): *Object*

*Inherited from [C8oBase](c8obase.md).[headers](c8obase.md#headers)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:184](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L184)*

**Returns:** *Object*

___

###  httpPublic

• **get httpPublic**(): *any*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:302](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L302)*

**Returns:** *any*

___

###  keepSessionAlive

• **get keepSessionAlive**(): *boolean*

*Inherited from [C8oBase](c8obase.md).[keepSessionAlive](c8obase.md#keepsessionalive)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:64](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L64)*

Gets if session has to be keep alive.<br/>
Default is <b>true</b>.

**Returns:** *boolean*

The KeepSessionAlive status.

___

###  log

• **get log**(): *[C8oLogger](c8ologger.md)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:218](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L218)*

**Returns:** *[C8oLogger](c8ologger.md)*

___

###  logC8o

• **get logC8o**(): *boolean*

*Overrides [C8oBase](c8obase.md).[logC8o](c8obase.md#logc8o)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:193](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L193)*

**Returns:** *boolean*

• **set logC8o**(`value`: boolean): *void*

*Overrides [C8oBase](c8obase.md).[logC8o](c8obase.md#logc8o)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:197](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L197)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | boolean |

**Returns:** *void*

___

###  logLevelLocal

• **get logLevelLocal**(): *[C8oLogLevel](c8ologlevel.md)*

*Overrides [C8oBase](c8obase.md).[logLevelLocal](c8obase.md#loglevellocal)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:210](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L210)*

**Returns:** *[C8oLogLevel](c8ologlevel.md)*

• **set logLevelLocal**(`value`: [C8oLogLevel](c8ologlevel.md)): *void*

*Overrides [C8oBase](c8obase.md).[logLevelLocal](c8obase.md#loglevellocal)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:214](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L214)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | [C8oLogLevel](c8ologlevel.md) |

**Returns:** *void*

___

###  logOnFail

• **get logOnFail**(): *function*

*Inherited from [C8oBase](c8obase.md).[logOnFail](c8obase.md#logonfail)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:172](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L172)*

**Returns:** *function*

▸ (`exception`: Error, `parameters`: Object): *void*

**Parameters:**

Name | Type |
------ | ------ |
`exception` | Error |
`parameters` | Object |

___

###  logRemote

• **get logRemote**(): *boolean*

*Overrides [C8oBase](c8obase.md).[logRemote](c8obase.md#logremote)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:201](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L201)*

**Returns:** *boolean*

• **set logRemote**(`value`: boolean): *void*

*Overrides [C8oBase](c8obase.md).[logRemote](c8obase.md#logremote)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:205](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L205)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | boolean |

**Returns:** *void*

___

###  normalizeParameters

• **get normalizeParameters**(): *boolean*

*Inherited from [C8oBase](c8obase.md).[normalizeParameters](c8obase.md#normalizeparameters)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:56](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L56)*

Gets if normalize parameters.<br/>
Default is <b>false</b>.

**Returns:** *boolean*

The timeout.

___

###  prefixBase

• **get prefixBase**(): *boolean*

*Overrides [C8oBase](c8obase.md).[prefixBase](c8obase.md#prefixbase)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:314](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L314)*

**Returns:** *boolean*

• **set prefixBase**(`resetBase`: boolean): *void*

*Overrides [C8oBase](c8obase.md).[prefixBase](c8obase.md#prefixbase)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:318](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L318)*

**Parameters:**

Name | Type |
------ | ------ |
`resetBase` | boolean |

**Returns:** *void*

___

###  resetBase

• **get resetBase**(): *boolean*

*Overrides [C8oBase](c8obase.md).[resetBase](c8obase.md#resetbase)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:306](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L306)*

**Returns:** *boolean*

• **set resetBase**(`resetBase`: boolean): *void*

*Overrides [C8oBase](c8obase.md).[resetBase](c8obase.md#resetbase)*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:310](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L310)*

**Parameters:**

Name | Type |
------ | ------ |
`resetBase` | boolean |

**Returns:** *void*

___

###  sdkVersion

• **get sdkVersion**(): *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:324](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L324)*

**Returns:** *string*

___

###  timeout

• **get timeout**(): *number*

*Inherited from [C8oBase](c8obase.md).[timeout](c8obase.md#timeout)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:101](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L101)*

Gets the connection timeout to Convertigo in milliseconds. A value of zero means the timeout is not used.<br/>
Default is <b>0</b>.

**Returns:** *number*

The timeout.

## Methods

###  _call

▸ **_call**(`parameters`: Object, `c8oResponseListener`: [C8oResponseListener](../interfaces/c8oresponselistener.md), `c8oExceptionListener`: [C8oExceptionListener](c8oexceptionlistener.md)): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:425](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L425)*

Makes a c8o call with c8o requestable in parameters ('__project' and ('__sequence' or ('__connector' and '__transaction'))).<br/>
To not use a C8oExceptionListener you can set the parameter to null.

**Parameters:**

Name | Type | Default | Description |
------ | ------ | ------ | ------ |
`parameters` | Object |  null | Contains c8o variables |
`c8oResponseListener` | [C8oResponseListener](../interfaces/c8oresponselistener.md) |  null | Define the behavior with the c8o call response |
`c8oExceptionListener` | [C8oExceptionListener](c8oexceptionlistener.md) |  null | Define the behavior when there is an exception during execution  |

**Returns:** *void*

___

###  addFullSyncChangeListener

▸ **addFullSyncChangeListener**(`db`: string, `listener`: [C8oFullSyncChangeListener](c8ofullsyncchangelistener.md)): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:602](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L602)*

Add a listener to monitor all changes of the 'db'.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`db` | string | the name of the fullsync database to monitor. Use the default database for a blank or a null value. |
`listener` | [C8oFullSyncChangeListener](c8ofullsyncchangelistener.md) | the listener to trigger on change.  |

**Returns:** *void*

___

###  addLive

▸ **addLive**(`liveid`: string, `db`: string, `task`: [C8oCallTask](c8ocalltask.md)): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:616](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L616)*

**Parameters:**

Name | Type |
------ | ------ |
`liveid` | string |
`db` | string |
`task` | [C8oCallTask](c8ocalltask.md) |

**Returns:** *void*

___

###  call

▸ **call**(`requestable`: string, `parameters`: Object, `c8oResponseListener`: [C8oResponseListener](../interfaces/c8oresponselistener.md), `c8oExceptionListener`: [C8oExceptionListener](c8oexceptionlistener.md)): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:377](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L377)*

Makes a c8o call with c8o requestable out of parameters.<br/>
To not use a C8oExceptionListener you can set the parameter to null

**Parameters:**

Name | Type | Default | Description |
------ | ------ | ------ | ------ |
`requestable` | string | - | Contains the Convertigo Sequence or Transaction targeted  (Syntax: "<project>.<sequence>" or "<project>.<connector>.<transaction>") |
`parameters` | Object |  null | Contains c8o variables |
`c8oResponseListener` | [C8oResponseListener](../interfaces/c8oresponselistener.md) |  null | Define the behavior with the c8o call response |
`c8oExceptionListener` | [C8oExceptionListener](c8oexceptionlistener.md) |  null | Define the behavior when there is an exception during execution  |

**Returns:** *void*

___

###  callJson

▸ **callJson**(`requestable`: string, ...`parameters`: any[]): *[C8oPromise](c8opromise.md)‹JSON›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:494](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L494)*

Makes a c8o call with c8o requestable out of parameters, expecting a JSON response through a C8oPromise.<br/>
The C8oPromise allow to register response handler with .then and .thenUI,
error handler with .fail and failUI,
replication handler with .progress
and synchronous response with .sync().

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`requestable` | string | Contains the Convertigo Sequence or Transaction targeted  (Syntax: "<project>.<sequence>" or "<project>.<connector>.<transaction>") |
`...parameters` | any[] | Contains c8o variables as key/value |

**Returns:** *[C8oPromise](c8opromise.md)‹JSON›*

A C8oPromise that can deliver the JSON response

___

###  callJsonObject

▸ **callJsonObject**(`requestable`: string, `parameters`: Object): *[C8oPromise](c8opromise.md)‹JSON›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:464](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L464)*

Makes a c8o call with c8o requestable out of parameters, expecting a JSON response through a C8oPromise.<br/>
The C8oPromise allow to register response handler with .then and .thenUI,
error handler with .fail and failUI,
replication handler with .progress
and synchronous response with .sync().

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`requestable` | string | Contains the Convertigo Sequence or Transaction targeted  (Syntax: "<project>.<sequence>" or "<project>.<connector>.<transaction>") |
`parameters` | Object | - |

**Returns:** *[C8oPromise](c8opromise.md)‹JSON›*

A C8oPromise that can deliver the JSON response

___

###  cancelLive

▸ **cancelLive**(`liveid`: string): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:623](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L623)*

**Parameters:**

Name | Type |
------ | ------ |
`liveid` | string |

**Returns:** *void*

___

###  copy

▸ **copy**(`c8oBase`: [C8oBase](c8obase.md)): *void*

*Inherited from [C8oBase](c8obase.md).[copy](c8obase.md#copy)*

*Defined in [c8osdk-js-core/src/c8o/c8oBase.ts:188](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oBase.ts#L188)*

**Parameters:**

Name | Type |
------ | ------ |
`c8oBase` | [C8oBase](c8obase.md) |

**Returns:** *void*

___

### `Protected` extractendpoint

▸ **extractendpoint**(): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:352](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L352)*

**Returns:** *void*

___

###  finalizeInit

▸ **finalizeInit**(): *Promise‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:752](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L752)*

This should be called OnPlatform Ready to remove splashscreen if necessary

**Returns:** *Promise‹any›*

___

###  get_attachment

▸ **get_attachment**(`id`: string, `attachment_name`: string, `database_name?`: string): *Promise‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:580](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L580)*

get an attachment for a given object

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |
`attachment_name` | string |
`database_name?` | string |

**Returns:** *Promise‹any›*

a promise containing a buffer

___

###  handleAutoLoginResponse

▸ **handleAutoLoginResponse**(): *Subject‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:568](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L568)*

Return an subject that call next if autologin is triggered with its result

**Returns:** *Subject‹any›*

___

###  handleCallException

▸ **handleCallException**(`c8oExceptionListener`: [C8oExceptionListener](c8oexceptionlistener.md), `requestParameters`: Object, `exception`: Error): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:536](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L536)*

Calls the exception listener callback if it is not null, else prints the exception stack trace.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`c8oExceptionListener` | [C8oExceptionListener](c8oexceptionlistener.md) | - |
`requestParameters` | Object | - |
`exception` | Error |   |

**Returns:** *void*

___

###  handleNetworkEvents

▸ **handleNetworkEvents**(): *Subject‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:561](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L561)*

Return an subject that call next if network has change

**Returns:** *Subject‹any›*

___

###  handleSessionLost

▸ **handleSessionLost**(): *Subject‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:546](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L546)*

Return an subject that call next if session has been lost

**Returns:** *Subject‹any›*

___

### `Abstract` httpGetObservable

▸ **httpGetObservable**(`uri`: any): *Observable‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:649](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L649)*

Method to bastract http get

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`uri` | any | the uri for given request  |

**Returns:** *Observable‹any›*

___

###  init

▸ **init**(`c8oSettings?`: [C8oSettings](c8osettings.md)): *Promise‹any›*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:666](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L666)*

This is the base object representing a Convertigo Server end point. This object should be instantiated
when the apps starts and be accessible from any class of the app. Although this is not common , you may have
several C8o objects instantiated in your app.

**`throws`** C8oException In case of invalid parameter or initialization failure.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`c8oSettings?` | [C8oSettings](c8osettings.md) | Initialization options.<br/>                    Example: new C8oSettings().setLogRemote(false).setDefaultDatabaseName("sample")  |

**Returns:** *Promise‹any›*

___

### `Abstract` initC8oHttInterface

▸ **initC8oHttInterface**(): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:654](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L654)*

Init http interface in client sdk

**Returns:** *void*

___

###  removeFullSyncChangeListener

▸ **removeFullSyncChangeListener**(`db`: string, `listener`: [C8oFullSyncChangeListener](c8ofullsyncchangelistener.md)): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:612](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L612)*

Remove a listener for changes of the 'db'.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`db` | string | the name of the fullsync database to monitor. Use the default database for a blank or a null value. |
`listener` | [C8oFullSyncChangeListener](c8ofullsyncchangelistener.md) | the listener instance to remove.  |

**Returns:** *void*

___

###  removeNull

▸ **removeNull**(`parameters`: any): *void*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:520](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L520)*

Remove null value from parameters

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`parameters` | any | an object |

**Returns:** *void*

a Map that contains all parameters

___

###  toString

▸ **toString**(): *string*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:222](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L222)*

**Returns:** *string*

___

### `Static` toParameters

▸ **toParameters**(`parameters`: any): *Object*

*Defined in [c8osdk-js-core/src/c8o/c8oCore.ts:504](https://github.com/convertigo/c8osdk-angular/blob/ffab8e3/src/c8o/c8oCore.ts#L504)*

Transforms siblings values as key/value of a Map.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`parameters` | any | pair of values to transform a object |

**Returns:** *Object*

a Map that contains all parameters