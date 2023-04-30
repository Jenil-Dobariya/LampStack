# Layer 1 : Application Layer

It provides services of Network Application.

## Services : 

1. File Transfer : It is done with the help of FTP(File Transfer Protocol).
2. Web surfing : It is done with the help of HTTP/HTTPS.
3. E-mails : It is done by SMTP.
4. Virtual Terminal : Telnet is used for it.

# Layer 2 : Presentation Layer

This layer receives data from application layer.

## Services :

1. Translation : Data is translated to machine understandable language.
2. Data compression : Data is compressed to increase the tranfer speed.
3. Encryption / Decryption : Encryption of data increases security. It is done by SSL protocol.

# Layer 3 : Session Layer

It helps in setting up and managing connections, sendin and receiving data followed by termination of connection. It uses APIs for its work.

## Services :

1. Authentication : Before establishment of session, authentication of user occurs.
2. Authorization : Server checks if you have permission to access a file or not.
3. Session Management : Session layer helps in making session with web server to download data packets and keeps track where the data packet goes.

# Layer 4 : Transport Layer

It control the reliability of Communication through segmentation, Flow control and Error control. It passes data to the network layer.

1. Segmentation : Data divides into small data units called segments.
2. Flow Control : Manage the speed of data transfer.
3. Error Control : If some data segments is not missing, the layer uses Automatic Repeat Request scheme to find missing data.

## Services :

1. Connection-oriented Transmission : It uses TCP (Transmission Control Protocol). It provides feedback if data is transmitted or not for error control.
2. Connectionless Transmissin : It uses UDP (User Datagram Protocol). It doesn't provide feedback. Data is completely received or not doesn't matter here.

# Layer 5 : Network Layer

It works for the transmission of data received from Transport Layer from one device to another which is located in different networks.

## Services :

1. Logical Addressing : IP addressing done in this layer is called logical addressing.
2. Routing : It is a method to move data packets to source to destination.
3. Path determination : Choosing best (shortest) path for data delivery is called as path determination. It uses protocols like, OSF, BGP, IS-IS.

# Layer 6 : Data link Layer

It receives data packets from network layer. It uses physical addressing where MAC addresses of sender and receiver assigns to data packet to make a frame.

## Services :

1. Framing : This layer uses framing to transfer data.
2. Media Access control and Error Detection : controls how data is placed and received from the media.

# Layer 7 : Physical Layer

It converts binary sequence of data into signals and transmits over media. Signal generated in this layer depends on type of media used to connect two devices. At the side of the receiver, This layer receives signal and converts it into binary sequence and sends it to data link layer.


