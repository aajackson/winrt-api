---
-api-id: T:Windows.Devices.Sms.SmsMessageType
-api-type: winrt enum
---

<!-- Enumeration syntax
public enum Windows.Devices.Sms.SmsMessageType : int
-->

# SmsMessageType

## -description
This enumerated type defines the format of the SMS message.

> [!NOTE]
> This functionality is only available to mobile operator apps and Windows Store app given privileged access by mobile network operators, mobile broadband adapter IHV, or OEM. For more information, see [Mobile Broadband:  device apps](http://msdn.microsoft.com/library/windows/hardware/hh852368.aspx).

## -enum-fields
### -field Binary:0
The SMS message is in binary format.

### -field Text:1
The SMS message is in text format.

### -field Wap:2
A WAP Push message (an MMS message, for example). This value is supported on Windows Store app and Windows Phone Store app on Windows 10.

### -field App:3
An application-directed message (a visual voicemail message on a specific port, for example). This value is supported on Windows Store app and Windows Phone Store app on Windows 10.

### -field Broadcast:4
A cell broadcast message. This value is supported on Windows Store app and Windows Phone Store app on Windows 10.

### -field Voicemail:5
A legacy voicemail message waiting indication message.

This value is supported on Windows Store app and Windows Phone Store app on Windows 10.

### -field Status:6
A send status message. This value is supported on Windows Store app and Windows Phone Store app on Windows 10.


## -remarks

## -examples

## -see-also


## -capabilities
sms, cellularMessaging