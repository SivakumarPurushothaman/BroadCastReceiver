# BroadCastReceiver
Broadcast Receiver with Manifest Declaration, Code Declaration, Post Oreo, Local Broadcast Receiver, Broadcast Receiver with priority



# BroadCastReceiver - It only listens only when it is registered.
Broadcast Receiver - Its a listener which generate the particular events are triggered. particular events would be system generated events or custom events.

Events - Intents .
Listener - BroadcastListener

Intent is triggered – Intent is broadcast
Broadcast Receiver is need to placed in the manifest file or in the code.
Broadcast Receiver –Listen via Intent   System Events Battery low, Incoming call, Incoming Message, Wifi Connected, Bluetooth Connected, Charger Connected.

Broadcast Receiver is in Manifest. File.
And also Intent Filter  Action
Broadcast Receiver is in Code.
Broadcast Receiver is by custom intent.
<receiver exported = false>, Local Broadcast Receiver
Normal Broadcast Receiver
ordered Broadcast Receiver with Priority

