# BiTRe
This repository release some results in the paper BiTRe

## CBI's Interface Complexity in Android 11.0.0_r1
| CBI |  Interface Complexity   |  read cap   | write cap  |
| ---- | ----- | ----- | ----- | 
| IMediaPlayer | 875 | {'RC', 'RI', 'RP', 'RA'} | {'WA', 'WP'} | 
| IRemoteDisplayClient | 506 | {'RI', 'RP', 'RA'} | {'WP'} | 
| IGraphicBufferProducer | 492 | {'RC', 'RI', 'RP', 'RA'} | {'WA', 'WP'} | 
| IIdentityCredential | 382 | {'RC', 'RP', 'RA'} | {'WA', 'WP'} | 
| ICredential | 282 | {'RC', 'RP', 'RA'} | {'WA', 'WP'} | 
| IWifiScannerImpl | 233 | {'RC', 'RI', 'RP', 'RA'} | {'WA', 'WP'} | 
| IWritableIdentityCredential | 223 | {'RC', 'RP', 'RA'} | {'WA', 'WP'} | 
| IVoldTaskListener | 208 | {'RC', 'RP', 'RA'} | {'WA', 'WP'} | 
| INetdEventListener | 177 | {'RC', 'RP', 'RA'} | {'WA', 'WP'} | 
| IImageService | 169 | {'RC', 'RI', 'RP', 'RA'} | {'WA', 'WP'} | 
| IConsumerListener | 164 | {'RC', 'RP', 'RA'} | {'WP'} | 
| INetdUnsolicitedEventListener | 162 | {'RC', 'RP', 'RA'} | {'WA', 'WP'} | 
| IVoldListener | 150 | {'RP', 'RA'} | {'WA', 'WP'} | 
| IWritableCredential | 125 | {'RC', 'RP', 'RA'} | {'WA', 'WP'} | 
| IDataLoader | 123 | {'RC', 'RI', 'RP', 'RA'} | {'WA', 'WP'} | 
| ICameraDeviceCallbacks | 122 | {'RC', 'RP', 'RA'} | {'WA', 'WP'} | 
| IMediaExtractor | 80 | {'RC', 'RP', 'RA'} | {'WI', 'WA', 'WP'} | 
| IStreamSource | 77 | {'RC', 'RI', 'RP', 'RA'} | {'WP'} | 
| IPendingIntentRef | 56 | {'RC', 'RP', 'RA'} | {'WA'} | 
| ICameraServiceListener | 54 | {'RP', 'RA'} | {'WA', 'WP'} | 
| ICameraRecordingProxyListener | 54 | {'RC', 'RI', 'RP', 'RA'} | {'WP'} | 
| IApInterface | 50 | {'RI', 'RP', 'RA'} | {'WA', 'WP'} | 
| IStreamListener | 50 | {'RP', 'RA'} | {'WP'} | 
| IKeystoreKeyCharacteristicsCallback | 34 | {'RP', 'RA'} | {'WA', 'WP'} | 
| IOMXBufferSource | 34 | {'RP', 'RA'} | {'WA', 'WP'} | 
| ITaskListener | 34 | {'RP', 'RA'} | {'WA', 'WP'} | 
| ICredstoreTokenCallback | 32 | {'RC', 'RP', 'RA'} | {'WA', 'WP'} | 
| IDumpstateListener | 31 | {'RP', 'RA'} | {'WA', 'WP'} | 
| IMediaPlayerClient | 31 | {'RP', 'RA'} | {'WP'} | 
| IDataSource | 31 | {'RP'} | {'WI', 'WA', 'WP'} | 
| IPullAtomCallback | 28 | {'RI', 'RP', 'RA'} | {'WA'} | 
| IApInterfaceEventCallback | 28 | {'RC', 'RP', 'RA'} | {'WA', 'WP'} | 
| IKeystoreCertificateChainCallback | 28 | {'RP', 'RA'} | {'WA', 'WP'} | 
| IKeystoreOperationResultCallback | 27 | {'RI', 'RP', 'RA'} | {'WA', 'WP'} | 
| IPullAtomResultReceiver | 23 | {'RC', 'RP', 'RA'} | {'WA'} | 
| IAudioFlingerClient | 23 | {'RP', 'RA'} | {'WP'} | 
| IIncidentReportStatusListener | 22 | {'RP'} | {'WA', 'WP'} | 
| IPackageChangeObserver | 21 | {'RP', 'RA'} | {'WA', 'WP'} | 
| IAudioTrackCallback | 18 | {'RC', 'RP', 'RA'} | {'WA', 'WP'} | 
| IVoldMountCallback | 17 | {'RP', 'RA'} | {'WA', 'WP'} | 
| IKeystoreExportKeyCallback | 17 | {'RP', 'RA'} | {'WA', 'WP'} | 
| IPackageInstallerSessionFileSystemConnector | 17 | {'RP', 'RA'} | {'WA', 'WP'} | 
| IThermalEventListener | 17 | {'RP', 'RA'} | {'WA', 'WP'} | 
| IProducerListener | 16 | {'RC', 'RP', 'RA'} | {'WP'} | 
| IUidObserver | 13 | {'RP'} | {'WP'} | 
| IUpdateEngineCallback | 13 | {'RP'} | {'WA', 'WP'} | 
| IKeystoreResponseCallback | 13 | {'RP', 'RA'} | {'WA', 'WP'} | 
| IIncidentDumpCallback | 12 | {'RP', 'RA'} | {'WA', 'WP'} | 
| IExternalVibrationController | 12 | {'RP'} | {'WA', 'WP'} | 
| ISendMgmtFrameEvent | 12 | {'RP'} | {'WA', 'WP'} | 
| IMountServiceListener | 12 | {'RP', 'RA'} | {'WP'} | 
| IVibratorCallback | 12 | {'RP', 'RA'} | {'WA'} | 
| IDrmServiceListener | 10 | {'RP', 'RA'} | {'WP'} | 
| IIncidentAuthListener | 10 | {} | {'WA', 'WP'} | 
| IResourceManagerClient | 10 | {'RP', 'RA'} | {'WA'} | 
| IScanEvent | 10 | {} | {'WA', 'WP'} | 
| IEffectClient | 10 | {'RP'} | {'WP'} | 
| IMediaHTTPService | 10 | {} | {'WA'} | 
| IServiceCallback | 10 | {'RI', 'RP', 'RA'} | {'WA', 'WP'} | 
| IPnoScanEvent | 10 | {} | {'WA', 'WP'} | 
| IMemory | 8 | {'RP'} | {'WI', 'WA'} | 
| IProgressCallback | 7 | {'RP'} | {'WA', 'WP'} | 
| IDataLoaderStatusListener | 7 | {'RP'} | {'WA', 'WP'} | 
| IIncrementalServiceConnector | 7 | {'RP'} | {'WA', 'WP'} | 
| IStorageHealthListener | 7 | {'RP'} | {'WA', 'WP'} | 
| ISuspendCallback | 6 | {'RP'} | {'WA', 'WP'} | 
| IObbActionListener | 6 | {'RP', 'RA'} | {'WP'} | 
| IThermalStatusListener | 6 | {'RP'} | {'WA', 'WP'} | 
| ICaptureStateListener | 6 | {'RP'} | {'WA', 'WP'} | 
| IClientCallback | 6 | {'RI', 'RP'} | {'WA', 'WP'} | 
| ISensorPrivacyListener | 6 | {'RP'} | {'WA', 'WP'} | 
| IGsiServiceCallback | 6 | {'RP'} | {'WA', 'WP'} | 
| IOemNetdUnsolicitedEventListener | 5 | {} | {'WA', 'WP'} | 
| ICameraOfflineSession | 5 | {} | {'WA', 'WP'} | 
| IAppOpsCallback | 5 | {'RP', 'RA'} | {'WP'} | 
| IMediaRecorderClient | 4 | {'RP'} | {'WP'} | 
| IAAudioClient | 4 | {'RP'} | {'WP'} | 
| IVsyncCallback | 2 | {'RP'} | {'WP'} | 
| IVrStateCallbacks | 2 | {'RP'} | {'WP'} | 
| IRegionSamplingListener | 2 | {'RP'} | {'WP'} | 
| IMountShutdownObserver | 2 | {'RP'} | {'WP'} | 
| IPersistentVrStateCallbacks | 2 | {'RP'} | {'WP'} | 
| ISetInputWindowsListener | 1 | {} | {'WP'} | 
