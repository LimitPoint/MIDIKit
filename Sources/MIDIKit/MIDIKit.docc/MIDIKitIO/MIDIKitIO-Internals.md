# Internals

## Topics

### MIDIManager Managed Objects

- ``MIDIInput``
- ``MIDIOutput``
- ``MIDIInputConnection``
- ``MIDIOutputConnection``
- ``MIDIThruConnection``

### Provider Classes and Types

- ``MIDIDevices``
- ``MIDIEndpoints``

### Supporting Types

- ``MIDIInputConnectionMode``
- ``MIDIOutputConnectionMode``
- ``MIDIEndpointType``

### MIDI Packets and Parsing

- ``MIDIPacketData``
- ``UniversalMIDIPacketData``
- ``MIDIUMPMessageType``
- ``MIDIUMPSysExStatusField``
- ``MIDIUMPUtilityStatusField``
- ``MIDIUMPMixedDataSetStatusField``
- ``AnyMIDIPacket``
- ``MIDI1Parser``
- ``MIDI2Parser``
- ``MIDIProtocolVersion``

### Core MIDI Related

- ``CoreMIDIAPIVersion``
- ``CoreMIDIClientRef``
- ``CoreMIDIObjectRef``
- ``CoreMIDIPortRef``
- ``CoreMIDIDeviceRef``
- ``CoreMIDIEntityRef``
- ``CoreMIDIEndpointRef``
- ``CoreMIDIThruConnectionRef``
- ``CoreMIDITimeStamp``
- ``CoreMIDIOSStatus``

### Errors

- ``MIDIIOError``
- ``MIDIOSStatus``

### I/O

- ``MIDIIOObject``
- ``MIDIIOObjectType``
- ``AnyMIDIIOObject``

- ``MIDIEndpoint``
- ``MIDIDevicesProtocol``
- ``MIDIEndpointsProtocol``
- ``MIDIManaged``
- ``MIDIManagedReceivesMessages``
- ``MIDIManagedSendsMessages``
