## TCP
- reception acknowledged, packets ordered
- TCP's congestion avoidance algorithm causes the sender to reduce its sending rate by a factor of two when it sees a packet loss.
- Symetrically, it tries to improve the rate by performing, on packets ACK, addititive increases of the number of unacknowledged packets that are sent over the network.
- TCP starts with a slow rate, but ramp up quickly. It also sleeps for Xms between sends.

## UDP
- no reception check, packets unordered, faster
- faster than TCP, better for voice over IP, video streaming

## DNS
- use UDP protocol, but can fall back to TCP

Also cf. **software_defined_networking.md**