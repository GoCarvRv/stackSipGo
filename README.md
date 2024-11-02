# gosip-extended Now is `stackSipGo`
Version: 0.2  
*Fork of the original [gosip project](https://github.com/jart/gosip)*

## About
This is a fork of the gosip library that aims to extend the original functionality with support for additional RFCs and modern SIP implementations. While the original project provided an excellent foundation for basic SIP/RTP implementation, this fork will focus on expanding the protocol support and adding new features.

The original gosip (pronounced "gossip") is a library for making phone calls using the Go programming language, primarily focused on PSTN calls through services like Flowroute. This fork maintains all the original capabilities while expanding the protocol support.

### Key Features from Original Project
- Full-stack SIP/RTP implementation
- SSE optimised audio mixing
- Assembly implementation of µLaw codec
- Excellent SRV/NAPTR failover support
- Mid-call audio/signalling path changes
- Ragel-based SIP message parsing
- Lightweight and suitable for per-call process design

### New Direction
This fork will focus on:
- Implementing additional SIP-related RFCs
- Expanding codec support beyond µLaw
- Enhancing security features
- Adding modern SIP extensions
- Improving WebRTC compatibility
- Supporting additional transport protocols

## Currently Supported RFCs
### Core RFCs (From Original)
- [RFC3261: SIP](https://tools.ietf.org/html/rfc3261)
- [RFC4566: SDP](https://tools.ietf.org/html/rfc4566)
- [RFC3550: RTP](https://tools.ietf.org/html/rfc3550)
- [RFC4733: RTP DTMF](https://tools.ietf.org/html/rfc4733)
- [RFC3262: SIP 100rel](https://tools.ietf.org/html/rfc3262)
- [RFC3263: SIP: Locating a Server](https://tools.ietf.org/html/rfc3263)

### New/Planned RFC Support
- [RFC3311: SIP UPDATE Method](https://tools.ietf.org/html/rfc3311)
- [RFC3326: Reason Header Field](https://tools.ietf.org/html/rfc3326)
- [RFC3515: SIP REFER Method](https://tools.ietf.org/html/rfc3515)
- [RFC3891: SIP Replaces Header](https://tools.ietf.org/html/rfc3891)
- [RFC4028: Session Timers](https://tools.ietf.org/html/rfc4028)
- [RFC6665: SIP-Specific Event Notification](https://tools.ietf.org/html/rfc6665)
- More RFCs to be added based on community needs

## Contributing
We welcome contributions! Please feel free to submit pull requests, especially for:
- Implementation of new RFCs
- Bug fixes
- Performance improvements
- Documentation improvements
- Test coverage expansion

## License
*[Apache-2.0 license]*

## Credits
This project is based on the original gosip project by [Jart (Justine Tunney)]. We maintain the original codebase's integrity while expanding its capabilities in new directions.
