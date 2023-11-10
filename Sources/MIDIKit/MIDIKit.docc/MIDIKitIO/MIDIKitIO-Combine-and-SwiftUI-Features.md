# Combine and SwiftUI Features

Certain objects and properties are observable.

``ObservableMIDIManager`` is a ``MIDIManager`` subclass that contains several instance properties that are observable in a Combine or SwiftUI context. This can be useful in updating user interface displaying a list of MIDI endpoints in real-time as endpoints are added or removed from the system, for example.

- ``ObservableMIDIManager/observableDevices``
- ``ObservableMIDIManager/observableEndpoints``

Where use of Combine is not possible, notifications of changes can be received by storing a handler closure in ``MIDIManager/notificationHandler`` where you might then update user interface to reflect the new collection of endpoints.
