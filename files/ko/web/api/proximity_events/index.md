---
title: Proximity Events
slug: Web/API/Proximity_Events
original_slug: WebAPI/Proximity
---

{{DefaultAPISidebar("Proximity Events")}}{{Deprecated_Header}}

> **Warning:** The Proximity Events APIs are not supported by any current major browser, and should not be used. This page is provided for historical interest.

근접 이벤트는 사용자가 디바이스에 가까이 갔을 때를 알 수 있는 간단한 방법이다. 예를 들어, 사용자에게 전화가 걸려왔을 때 디바이스에 귀를 가까이하면, 근접 이벤트들은 스마트폰의 화면이 꺼지게 하여 이러한 변화에 대응할 수 있게 해준다.

근접 링크는 두 가지가 있다. (문서를 확인하려먼 링크를 참고하시오.):

- {{domxref("UserProximityEvent")}}, handled by `window.onuserproximity`
- {{domxref("DeviceProximityEvent")}}, handled by `window.ondeviceproximity`

두 가지의 차이점은 {{domxref("UserProximityEvent")}} 은 유저가 "가깝다"고 여겨질 때 단순히 `true`라고 알려주는 반면에, {{domxref("DeviceProximityEvent")}}는 근처 객체의 실제 거리 추정치를 제공한다.

> **참고:** 당연히 이 API는 근접 센서를 가진 장치를 필요로 하며, 이 근접 센서는 대게 모바일 다비이스들에서만 이용 가능하다. 근접 센서가 없는 장치들에서는 근접 이벤트들을 지원할 수는 있을 지 몰라도 해당 이벤트들은 절대 발생하지 않을 것이다.

## Specifications

{{Specifications}}
