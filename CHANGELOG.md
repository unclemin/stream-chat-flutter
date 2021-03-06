## 0.1.35

- Add backgroundColor as part of StreamChatThemeData

## 0.1.34

- Add `onUserAvatarTap`

## 0.1.33

- Add default user and channel image to `StreamChatTheme`

## 0.1.32

- Update llc version

## 0.1.31

- Add `initialMessage` property to `MessageInput`

## 0.1.30

- Add simple rendering of file attachments

## 0.1.29

- Add `doImageUploadRequest` and `doFileUploadRequest` to `MessageInput` to let users customize file uploading (eg: custom cdn)

## 0.1.28

- Add `onTap` to `ChannelImage`

- Add `onImageTap` and `onTitleTap` to `ChannelHeader`

- Add `onImageTap` to `ChannelListView`

## 0.1.27

- Show other member user's name and image in one to one channels

## 0.1.25

- Fix overflow in mentions overlay

## 0.1.23

- Hotfix

## 0.1.22

- Better mime type detection

## 0.1.21

- Fix video loading and error

## 0.1.20

- Add message configuration properties to MessageListView

## 0.1.19

- Fix video aspect ratio

- Add property to decide whether to enable video fullscreen

- Add property to hide the attachment button

- Do not show send button if an attachment is still uploading

- Unfocus and disable the TextField before opening the camera (workaround for flutter/flutter#42417)

- Add gesture (vertical drag down) to close the keyboard

- Add keyboard type parameters (set it to TextInputType.text to show the submit button that will even close the keyboard)

The property showVideoFullScreen was added mainly because of this issue brianegan/chewie#261

## 0.1.18

- Add message list date separators

## 0.1.17

- Add dark theme

## 0.1.16

- Add possibility to show the other users username next to the message timestamp

## 0.1.15

- Fix MessageInput overflow

## 0.1.14

- Add automatic keep alive to streamchat

## 0.1.12

- Fix dependency error on iOS using flutter_form_builder

## 0.1.11

- Fix bug in ChannelPreview when list of messages is empty

## 0.1.10

- Do not automatically dispose Client object when disposing StreamChat widget

## 0.1.9

- Fix message ui overflow

## 0.1.8

- Bug fix

## 0.1.7

- Add chat commands

- Add edit message

## 0.1.6+4

- Add some documentation

## 0.1.5

- Fix channels pagination

## 0.1.4

- Fix message widget builder on reaction

## 0.1.3

- Fix upload attachment

## 0.1.2

- Fix avatar shape

## 0.1.1

- Add ThreadHeader

## 0.0.1

- First release