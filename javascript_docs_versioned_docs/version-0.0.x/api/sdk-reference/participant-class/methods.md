---
title: Participant Class Methods
sidebar_position: 1
sidebar_label: Methods
pagination_label: Participant Class Methods
---

<div class="sdk-api-ref-only-h4">

### enableWebcam()

- `enableWebcam()` is used to enable participant's camera.

#### Events associated with `enableWebcam()` :

- First the participant will get a callback on [`webcam-requested`](../meeting-class/events#webcam-requested) and once the participant accepts the request, webcam will be enabled.

- Every Participant will receive a `stream-enabled` event with `stream` object.

#### Returns

- `void`

---

### disableWebcam()

- `disableWebcam()` is used to disable participant camera.

#### Events associated with `disableWebcam()` :

- Every Participant will receive a `stream-disabled` event with `stream` object.

#### Returns

- `void`

---

### enableMic()

- `enableMic()` is used to enable participant microphone.

#### Events associated with `enableMic()` :

- First the participant will get a callback on [`mic-requested`](../meeting-class/events#mic-requested) and once the participant accepts the request, mic will be enabled.

- Every Participant will receive a `stream-enabled` event with `stream` object.

#### Returns

- `void`

---

### disableMic()

- `disableMic()` is used to disable participant microphone.

#### Events associated with `disableMic()`:

- Every Participant will receive a `stream-disabled` event with `stream` object.

#### Returns

- `void`

---

### setQuality()

- `setQuality()` is used to set the quality of the participant's video stream.

#### Parameters

- `quality`: low | med | high

#### Returns

- `void`

---

</div>
