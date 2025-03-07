# Circuit Switching

## What is Circuit Switching?
Circuit switching is a method of communication where a dedicated communication path is established between two devices before data transfer begins.

## How Circuit Switching Works
1. **Setup Phase**: A dedicated path is established between the sender and receiver.
2. **Data Transfer Phase**: Data is transmitted over the established path.
3. **Teardown Phase**: The dedicated path is released after data transfer is complete.

## Advantages of Circuit Switching
- **Guaranteed Bandwidth**: The dedicated path ensures consistent bandwidth.
- **Low Latency**: Minimal delay during data transfer.
- **Reliability**: Suitable for real-time applications like voice calls.

## Disadvantages of Circuit Switching
- **Inefficient Use of Resources**: The dedicated path remains reserved even when no data is being transmitted.
- **Scalability**: Limited by the number of available circuits.
- **Cost**: Expensive to maintain dedicated paths.

## Applications of Circuit Switching
- **Traditional Telephone Networks**: Uses circuit switching for voice calls.
- **ISDN (Integrated Services Digital Network)**: Uses circuit switching for voice and data communication.
- **Leased Lines**: Provides dedicated connections for businesses.

## Comparison with Packet Switching
| **Aspect**            | **Circuit Switching**         | **Packet Switching**          |
|------------------------|-------------------------------|-------------------------------|
| **Resource Usage**     | Inefficient                  | Efficient                     |
| **Latency**            | Low                          | Variable                      |
| **Scalability**        | Limited                      | High                         