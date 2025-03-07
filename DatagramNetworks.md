# Datagram Networks

## What are Datagram Networks?
Datagram networks are a type of packet-switched network where each packet (datagram) is treated independently and routed based on its destination address.

## Characteristics of Datagram Networks
- **Connectionless**: No dedicated path is established before data transfer.
- **Independent Packets**: Each packet is routed independently.
- **Best-Effort Delivery**: No guarantee of packet delivery or order.

## Advantages of Datagram Networks
- **Efficiency**: Resources are used only when data is transmitted.
- **Scalability**: Can handle large amounts of data.
- **Flexibility**: Packets can take different routes to the destination.

## Disadvantages of Datagram Networks
- **Unreliable**: No guarantee of packet delivery or order.
- **Variable Delay**: Packets may experience different delays.
- **Complexity**: Requires advanced routing algorithms.

## Applications of Datagram Networks
- **Internet**: Uses IP for global communication.
- **VoIP (Voice over IP)**: Uses datagram networks for voice communication.
- **Video Streaming**: Uses datagram networks for real-time video transmission.

## Comparison with Virtual Circuit Networks
| **Aspect**            | **Datagram Networks**         | **Virtual Circuit Networks**  |
|------------------------|-------------------------------|-------------------------------|
| **Connection**         | Connectionless               | Connection-oriented           |
| **Packet Routing**     | Independent                  | Follows a dedicated path      |
| **Reliability**        | Best-effort delivery         | Guaranteed delivery           |
| **Use Case**           | Internet, VoIP               | ATM, Frame Relay              |

## Challenges in Datagram Networks
- **Routing**: Requires efficient algorithms to determine the best path.
- 