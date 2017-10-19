
# Back to main page: http://bit.ly/2yQxJpo

# Output from command: ./byfn.sh -m up
~~~
Arnes-MBP:first-network arnelennartfrantzell$ ./byfn.sh -m up
Starting with channel 'mychannel' and CLI timeout of '10000'
Continue (y/n)? y
proceeding ...
Creating peer0.org2.example.com ... 
Creating peer1.org1.example.com ... 
Creating orderer.example.com ... 
Creating peer1.org2.example.com ... 
Creating peer0.org1.example.com ... 
Creating peer1.org2.example.com
Creating peer0.org2.example.com
Creating orderer.example.com
Creating peer1.org1.example.com
Creating peer1.org1.example.com ... done
Creating cli ... 
Creating cli ... done

 ____    _____      _      ____    _____ 
/ ___|  |_   _|    / \    |  _ \  |_   _|
\___ \    | |     / _ \   | |_) |   | |  
 ___) |   | |    / ___ \  |  _ <    | |  
|____/    |_|   /_/   \_\ |_| \_\   |_|  

Build your first network (BYFN) end-to-end test

Channel name : mychannel
Creating channel...
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org1MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/users/Admin@org1.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer0.org1.example.com:7051
2017-10-19 17:21:07.188 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:21:07.189 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:21:07.200 UTC [channelCmd] InitCmdFactory -> INFO 003 Endorser and orderer connections initialized
2017-10-19 17:21:07.202 UTC [msp] GetLocalMSP -> DEBU 004 Returning existing local MSP
2017-10-19 17:21:07.202 UTC [msp] GetDefaultSigningIdentity -> DEBU 005 Obtaining default signing identity
2017-10-19 17:21:07.202 UTC [msp] GetLocalMSP -> DEBU 006 Returning existing local MSP
2017-10-19 17:21:07.202 UTC [msp] GetDefaultSigningIdentity -> DEBU 007 Obtaining default signing identity
2017-10-19 17:21:07.202 UTC [msp/identity] Sign -> DEBU 008 Sign: plaintext: 0A88060A074F7267314D535012FC052D...53616D706C65436F6E736F727469756D 
2017-10-19 17:21:07.202 UTC [msp/identity] Sign -> DEBU 009 Sign: digest: 868FD39AC7AB37B175734FFDF17CD7B55F6F220F22666CD995F4B7073CB7A78E 
2017-10-19 17:21:07.203 UTC [msp] GetLocalMSP -> DEBU 00a Returning existing local MSP
2017-10-19 17:21:07.203 UTC [msp] GetDefaultSigningIdentity -> DEBU 00b Obtaining default signing identity
2017-10-19 17:21:07.203 UTC [msp] GetLocalMSP -> DEBU 00c Returning existing local MSP
2017-10-19 17:21:07.203 UTC [msp] GetDefaultSigningIdentity -> DEBU 00d Obtaining default signing identity
2017-10-19 17:21:07.203 UTC [msp/identity] Sign -> DEBU 00e Sign: plaintext: 0ABF060A1508021A060883BEA3CF0522...CC52F38A394D01818A532A805EE1719C 
2017-10-19 17:21:07.203 UTC [msp/identity] Sign -> DEBU 00f Sign: digest: 8D927FC4DA90BA2BB603BEC8A1253D0644F58C7D35BD1151B017E141AF7F93EA 
2017-10-19 17:21:07.299 UTC [msp] GetLocalMSP -> DEBU 010 Returning existing local MSP
2017-10-19 17:21:07.299 UTC [msp] GetDefaultSigningIdentity -> DEBU 011 Obtaining default signing identity
2017-10-19 17:21:07.299 UTC [msp] GetLocalMSP -> DEBU 012 Returning existing local MSP
2017-10-19 17:21:07.299 UTC [msp] GetDefaultSigningIdentity -> DEBU 013 Obtaining default signing identity
2017-10-19 17:21:07.299 UTC [msp/identity] Sign -> DEBU 014 Sign: plaintext: 0ABF060A1508021A060883BEA3CF0522...4F5552A06D9212080A021A0012021A00 
2017-10-19 17:21:07.299 UTC [msp/identity] Sign -> DEBU 015 Sign: digest: 06A676030D7958ED684312261A6A710CF53FEA899E60AF3CB5E81E798B5E6DC6 
2017-10-19 17:21:07.300 UTC [channelCmd] readBlock -> DEBU 016 Got status: &{NOT_FOUND}
2017-10-19 17:21:07.300 UTC [msp] GetLocalMSP -> DEBU 017 Returning existing local MSP
2017-10-19 17:21:07.300 UTC [msp] GetDefaultSigningIdentity -> DEBU 018 Obtaining default signing identity
2017-10-19 17:21:07.311 UTC [channelCmd] InitCmdFactory -> INFO 019 Endorser and orderer connections initialized
2017-10-19 17:21:07.511 UTC [msp] GetLocalMSP -> DEBU 01a Returning existing local MSP
2017-10-19 17:21:07.512 UTC [msp] GetDefaultSigningIdentity -> DEBU 01b Obtaining default signing identity
2017-10-19 17:21:07.512 UTC [msp] GetLocalMSP -> DEBU 01c Returning existing local MSP
2017-10-19 17:21:07.512 UTC [msp] GetDefaultSigningIdentity -> DEBU 01d Obtaining default signing identity
2017-10-19 17:21:07.512 UTC [msp/identity] Sign -> DEBU 01e Sign: plaintext: 0ABF060A1508021A060883BEA3CF0522...5EA30CC2CE3612080A021A0012021A00 
2017-10-19 17:21:07.512 UTC [msp/identity] Sign -> DEBU 01f Sign: digest: 0FC62B33BA5D6EA7079EF7A73FED086F2E2D3E54E45305C367F2911A77602133 
2017-10-19 17:21:07.519 UTC [channelCmd] readBlock -> DEBU 020 Received block: 0
2017-10-19 17:21:07.519 UTC [main] main -> INFO 021 Exiting.....
===================== Channel "mychannel" is created successfully ===================== 

Having all peers join the channel...
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org1MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/users/Admin@org1.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer0.org1.example.com:7051
2017-10-19 17:21:07.624 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:21:07.625 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:21:07.631 UTC [channelCmd] InitCmdFactory -> INFO 003 Endorser and orderer connections initialized
2017-10-19 17:21:07.632 UTC [msp/identity] Sign -> DEBU 004 Sign: plaintext: 0A86070A5C08011A0C0883BEA3CF0510...1209660B7B6E1A080A000A000A000A00 
2017-10-19 17:21:07.632 UTC [msp/identity] Sign -> DEBU 005 Sign: digest: 89B7CEEB1235524197BA5A3E65B6CE4075A5DB20527864D1E4E086C548F454AA 
2017-10-19 17:21:07.737 UTC [channelCmd] executeJoin -> INFO 006 Peer joined the channel!
2017-10-19 17:21:07.738 UTC [main] main -> INFO 007 Exiting.....
===================== PEER0 joined on the channel "mychannel" ===================== 

CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org1MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/users/Admin@org1.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer1.org1.example.com:7051
2017-10-19 17:21:10.845 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:21:10.845 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:21:10.851 UTC [channelCmd] InitCmdFactory -> INFO 003 Endorser and orderer connections initialized
2017-10-19 17:21:10.851 UTC [msp/identity] Sign -> DEBU 004 Sign: plaintext: 0A86070A5C08011A0C0886BEA3CF0510...1209660B7B6E1A080A000A000A000A00 
2017-10-19 17:21:10.852 UTC [msp/identity] Sign -> DEBU 005 Sign: digest: 48696757271B0B8DD5C60965997A509577495550EC481F8D6A8E88A05A387FB5 
2017-10-19 17:21:10.959 UTC [channelCmd] executeJoin -> INFO 006 Peer joined the channel!
2017-10-19 17:21:10.959 UTC [main] main -> INFO 007 Exiting.....
===================== PEER1 joined on the channel "mychannel" ===================== 

CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/peers/peer0.org2.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org2MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/users/Admin@org2.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer0.org2.example.com:7051
2017-10-19 17:21:14.056 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:21:14.056 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:21:14.063 UTC [channelCmd] InitCmdFactory -> INFO 003 Endorser and orderer connections initialized
2017-10-19 17:21:14.063 UTC [msp/identity] Sign -> DEBU 004 Sign: plaintext: 0A85070A5B08011A0B088ABEA3CF0510...1209660B7B6E1A080A000A000A000A00 
2017-10-19 17:21:14.063 UTC [msp/identity] Sign -> DEBU 005 Sign: digest: 25A4F150541946A0468E98136E7AADCACEAB0B9D89F4340F236C467DDA080EDD 
2017-10-19 17:21:14.181 UTC [channelCmd] executeJoin -> INFO 006 Peer joined the channel!
2017-10-19 17:21:14.182 UTC [main] main -> INFO 007 Exiting.....
===================== PEER2 joined on the channel "mychannel" ===================== 

CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/peers/peer0.org2.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org2MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/users/Admin@org2.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer1.org2.example.com:7051
2017-10-19 17:21:17.284 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:21:17.284 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:21:17.291 UTC [channelCmd] InitCmdFactory -> INFO 003 Endorser and orderer connections initialized
2017-10-19 17:21:17.291 UTC [msp/identity] Sign -> DEBU 004 Sign: plaintext: 0A86070A5C08011A0C088DBEA3CF0510...1209660B7B6E1A080A000A000A000A00 
2017-10-19 17:21:17.291 UTC [msp/identity] Sign -> DEBU 005 Sign: digest: 9D7700802A62E9C4715FC183B13CE4ADB285A415498723A951A242F07BD95BC0 
2017-10-19 17:21:17.407 UTC [channelCmd] executeJoin -> INFO 006 Peer joined the channel!
2017-10-19 17:21:17.407 UTC [main] main -> INFO 007 Exiting.....
===================== PEER3 joined on the channel "mychannel" ===================== 

Updating anchor peers for org1...
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org1MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/users/Admin@org1.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer0.org1.example.com:7051
2017-10-19 17:21:20.511 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:21:20.511 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:21:20.518 UTC [channelCmd] InitCmdFactory -> INFO 003 Endorser and orderer connections initialized
2017-10-19 17:21:20.522 UTC [msp] GetLocalMSP -> DEBU 004 Returning existing local MSP
2017-10-19 17:21:20.522 UTC [msp] GetDefaultSigningIdentity -> DEBU 005 Obtaining default signing identity
2017-10-19 17:21:20.522 UTC [msp] GetLocalMSP -> DEBU 006 Returning existing local MSP
2017-10-19 17:21:20.522 UTC [msp] GetDefaultSigningIdentity -> DEBU 007 Obtaining default signing identity
2017-10-19 17:21:20.522 UTC [msp/identity] Sign -> DEBU 008 Sign: plaintext: 0A88060A074F7267314D535012FC052D...2A0641646D696E732A0641646D696E73 
2017-10-19 17:21:20.522 UTC [msp/identity] Sign -> DEBU 009 Sign: digest: 3B39B0F25948404C79EA7B377FFFDE842B517578F7045E94724B6B8EBBE41971 
2017-10-19 17:21:20.522 UTC [msp] GetLocalMSP -> DEBU 00a Returning existing local MSP
2017-10-19 17:21:20.522 UTC [msp] GetDefaultSigningIdentity -> DEBU 00b Obtaining default signing identity
2017-10-19 17:21:20.522 UTC [msp] GetLocalMSP -> DEBU 00c Returning existing local MSP
2017-10-19 17:21:20.522 UTC [msp] GetDefaultSigningIdentity -> DEBU 00d Obtaining default signing identity
2017-10-19 17:21:20.522 UTC [msp/identity] Sign -> DEBU 00e Sign: plaintext: 0ABF060A1508021A060890BEA3CF0522...9188F6B5D769894AE6CD235DBD9535A4 
2017-10-19 17:21:20.523 UTC [msp/identity] Sign -> DEBU 00f Sign: digest: 8AE226DC74CD30F25428BDFFE07920E15EF5B9A201A61C3D0CF3CEB0C44C562A 
2017-10-19 17:21:20.563 UTC [main] main -> INFO 010 Exiting.....
===================== Anchor peers for org "Org1MSP" on "mychannel" is updated successfully ===================== 

Updating anchor peers for org2...
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/peers/peer0.org2.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org2MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/users/Admin@org2.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer0.org2.example.com:7051
2017-10-19 17:21:23.673 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:21:23.673 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:21:23.680 UTC [channelCmd] InitCmdFactory -> INFO 003 Endorser and orderer connections initialized
2017-10-19 17:21:23.684 UTC [msp] GetLocalMSP -> DEBU 004 Returning existing local MSP
2017-10-19 17:21:23.684 UTC [msp] GetDefaultSigningIdentity -> DEBU 005 Obtaining default signing identity
2017-10-19 17:21:23.684 UTC [msp] GetLocalMSP -> DEBU 006 Returning existing local MSP
2017-10-19 17:21:23.684 UTC [msp] GetDefaultSigningIdentity -> DEBU 007 Obtaining default signing identity
2017-10-19 17:21:23.684 UTC [msp/identity] Sign -> DEBU 008 Sign: plaintext: 0A88060A074F7267324D535012FC052D...2A0641646D696E732A0641646D696E73 
2017-10-19 17:21:23.684 UTC [msp/identity] Sign -> DEBU 009 Sign: digest: DE52BDB6F57553464A8590B7B0DB81C9258C7E38440738377E86960C39E5FAC2 
2017-10-19 17:21:23.684 UTC [msp] GetLocalMSP -> DEBU 00a Returning existing local MSP
2017-10-19 17:21:23.684 UTC [msp] GetDefaultSigningIdentity -> DEBU 00b Obtaining default signing identity
2017-10-19 17:21:23.685 UTC [msp] GetLocalMSP -> DEBU 00c Returning existing local MSP
2017-10-19 17:21:23.685 UTC [msp] GetDefaultSigningIdentity -> DEBU 00d Obtaining default signing identity
2017-10-19 17:21:23.685 UTC [msp/identity] Sign -> DEBU 00e Sign: plaintext: 0ABF060A1508021A060893BEA3CF0522...899DD1130188FBB0A7F1BD07808D5C49 
2017-10-19 17:21:23.685 UTC [msp/identity] Sign -> DEBU 00f Sign: digest: A5D73AF2B90E7274B6493BC69B7070CBBD1F0CD87FB4234591124A81FEF65B63 
2017-10-19 17:21:23.746 UTC [main] main -> INFO 010 Exiting.....
===================== Anchor peers for org "Org2MSP" on "mychannel" is updated successfully ===================== 

Installing chaincode on org1/peer0...
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org1MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/users/Admin@org1.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer0.org1.example.com:7051
2017-10-19 17:21:26.855 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:21:26.855 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:21:26.855 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 003 Using default escc
2017-10-19 17:21:26.855 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 004 Using default vscc
2017-10-19 17:21:27.174 UTC [golang-platform] getCodeFromFS -> DEBU 005 getCodeFromFS github.com/hyperledger/fabric/examples/chaincode/go/chaincode_example02
2017-10-19 17:21:27.648 UTC [golang-platform] func1 -> DEBU 006 Discarding GOROOT package fmt
2017-10-19 17:21:27.648 UTC [golang-platform] func1 -> DEBU 007 Discarding provided package github.com/hyperledger/fabric/core/chaincode/shim
2017-10-19 17:21:27.648 UTC [golang-platform] func1 -> DEBU 008 Discarding provided package github.com/hyperledger/fabric/protos/peer
2017-10-19 17:21:27.648 UTC [golang-platform] func1 -> DEBU 009 Discarding GOROOT package strconv
2017-10-19 17:21:27.651 UTC [golang-platform] GetDeploymentPayload -> DEBU 00a done
2017-10-19 17:21:27.657 UTC [msp/identity] Sign -> DEBU 00b Sign: plaintext: 0A86070A5C08031A0C0897BEA3CF0510...5F74FD270000FFFFCEF44F9B002C0000 
2017-10-19 17:21:27.657 UTC [msp/identity] Sign -> DEBU 00c Sign: digest: 6C08579D49DFF57AD6764ADEF265D7794D8CE873370763BE87FD3E6914A525B2 
2017-10-19 17:21:27.662 UTC [chaincodeCmd] install -> DEBU 00d Installed remotely response:<status:200 payload:"OK" > 
2017-10-19 17:21:27.662 UTC [main] main -> INFO 00e Exiting.....
===================== Chaincode is installed on remote peer PEER0 ===================== 

Install chaincode on org2/peer2...
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/peers/peer0.org2.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org2MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/users/Admin@org2.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer0.org2.example.com:7051
2017-10-19 17:21:27.772 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:21:27.772 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:21:27.772 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 003 Using default escc
2017-10-19 17:21:27.772 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 004 Using default vscc
2017-10-19 17:21:27.843 UTC [golang-platform] getCodeFromFS -> DEBU 005 getCodeFromFS github.com/hyperledger/fabric/examples/chaincode/go/chaincode_example02
2017-10-19 17:21:28.041 UTC [golang-platform] func1 -> DEBU 006 Discarding GOROOT package fmt
2017-10-19 17:21:28.041 UTC [golang-platform] func1 -> DEBU 007 Discarding provided package github.com/hyperledger/fabric/core/chaincode/shim
2017-10-19 17:21:28.041 UTC [golang-platform] func1 -> DEBU 008 Discarding provided package github.com/hyperledger/fabric/protos/peer
2017-10-19 17:21:28.041 UTC [golang-platform] func1 -> DEBU 009 Discarding GOROOT package strconv
2017-10-19 17:21:28.043 UTC [golang-platform] GetDeploymentPayload -> DEBU 00a done
2017-10-19 17:21:28.049 UTC [msp/identity] Sign -> DEBU 00b Sign: plaintext: 0A85070A5B08031A0B0898BEA3CF0510...5F74FD270000FFFFCEF44F9B002C0000 
2017-10-19 17:21:28.049 UTC [msp/identity] Sign -> DEBU 00c Sign: digest: 159BAA4E3A9F00D36E63CEC7EAB6D5DA6A9425CD02EE3ADA05DADF726D7B4E2A 
2017-10-19 17:21:28.055 UTC [chaincodeCmd] install -> DEBU 00d Installed remotely response:<status:200 payload:"OK" > 
2017-10-19 17:21:28.055 UTC [main] main -> INFO 00e Exiting.....
===================== Chaincode is installed on remote peer PEER2 ===================== 

Instantiating chaincode on org2/peer2...
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/peers/peer0.org2.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org2MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/users/Admin@org2.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer0.org2.example.com:7051
2017-10-19 17:21:28.150 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:21:28.150 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:21:28.157 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 003 Using default escc
2017-10-19 17:21:28.157 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 004 Using default vscc
2017-10-19 17:21:28.158 UTC [msp/identity] Sign -> DEBU 005 Sign: plaintext: 0A90070A6608031A0B0898BEA3CF0510...324D53500A04657363630A0476736363 
2017-10-19 17:21:28.158 UTC [msp/identity] Sign -> DEBU 006 Sign: digest: BABF3E3468D9238024C1B1C5AE54982C95DCDAEE998D8D6ECE2D66F5EE7606D5 
2017-10-19 17:21:44.379 UTC [msp/identity] Sign -> DEBU 007 Sign: plaintext: 0A90070A6608031A0B0898BEA3CF0510...DAD60E453D5B19A2004D9FC73E49883A 
2017-10-19 17:21:44.379 UTC [msp/identity] Sign -> DEBU 008 Sign: digest: 9FD35274AB547A8EE89DDFEB60C00FD9F1524F2E71779EF5433CCD3BCB1DE8C4 
2017-10-19 17:21:44.382 UTC [main] main -> INFO 009 Exiting.....
===================== Chaincode Instantiation on PEER2 on channel 'mychannel' is successful ===================== 

Querying chaincode on org1/peer0...
===================== Querying on PEER0 on channel 'mychannel'... ===================== 
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org1MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/users/Admin@org1.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer0.org1.example.com:7051
Attempting to Query PEER0 ...3 secs

2017-10-19 17:21:47.504 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:21:47.504 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:21:47.504 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 003 Using default escc
2017-10-19 17:21:47.504 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 004 Using default vscc
2017-10-19 17:21:47.504 UTC [msp/identity] Sign -> DEBU 005 Sign: plaintext: 0A91070A6708031A0C08ABBEA3CF0510...6D7963631A0A0A0571756572790A0161 
2017-10-19 17:21:47.504 UTC [msp/identity] Sign -> DEBU 006 Sign: digest: 1BE93256C1449C1AAD7D542F97CE7E0DA9A36D30E10F5123508A26BAD3AC4F2F 
Query Result: 100
2017-10-19 17:22:02.382 UTC [main] main -> INFO 007 Exiting.....
===================== Query on PEER0 on channel 'mychannel' is successful ===================== 
Sending invoke transaction on org1/peer0...
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org1MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/users/Admin@org1.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer0.org1.example.com:7051
2017-10-19 17:22:02.498 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:22:02.498 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:22:02.504 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 003 Using default escc
2017-10-19 17:22:02.504 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 004 Using default vscc
2017-10-19 17:22:02.505 UTC [msp/identity] Sign -> DEBU 005 Sign: plaintext: 0A91070A6708031A0C08BABEA3CF0510...696E766F6B650A01610A01620A023130 
2017-10-19 17:22:02.505 UTC [msp/identity] Sign -> DEBU 006 Sign: digest: 41165F3C0422A86B6DA32B228541795E103664D70F65BC646747C5A836E3A838 
2017-10-19 17:22:02.521 UTC [msp/identity] Sign -> DEBU 007 Sign: plaintext: 0A91070A6708031A0C08BABEA3CF0510...7032576502AAFE0C1F1EE437EB96DE90 
2017-10-19 17:22:02.521 UTC [msp/identity] Sign -> DEBU 008 Sign: digest: 0AFF32D3BE1E195EEB0E3E8A0742D189D2AEF5DBA0B36E6538D64DC94373FD23 
2017-10-19 17:22:02.525 UTC [chaincodeCmd] chaincodeInvokeOrQuery -> DEBU 009 ESCC invoke result: version:1 response:<status:200 message:"OK" > payload:"\n W\201\023\207\372\266\347W\207\272Z\023\026h\032\3652\277u\223>\236S\246\237$\244\331\262\215\334^\022Y\nE\022\024\n\004lscc\022\014\n\n\n\004mycc\022\002\010\003\022-\n\004mycc\022%\n\007\n\001a\022\002\010\003\n\007\n\001b\022\002\010\003\032\007\n\001a\032\00290\032\010\n\001b\032\003210\032\003\010\310\001\"\013\022\004mycc\032\0031.0" endorsement:<endorser:"\n\007Org1MSP\022\374\005-----BEGIN -----\nMIICGDCCAb+gAwIBAgIQI4NW5wRbzYu3RpWjqaDiMDAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xNzEwMTkxNzExNTRaFw0yNzEwMTcxNzExNTRa\nMFsxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMR8wHQYDVQQDExZwZWVyMC5vcmcxLmV4YW1wbGUuY29tMFkw\nEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAENIzbzotN8LgOr2akO+RgimB1rjWx3w4w\n8N5RI96vDLuhxuwGASGxiEz9dFrBmppAHCbBJjPmsaUcpo4lYVIN+6NNMEswDgYD\nVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAgKby1ohMNoeT2\nEI5DMjtlDKbdutujJocFH4djYaMbqZIwCgYIKoZIzj0EAwIDRwAwRAIgb+AILda6\n3LsoQMC+gKwkyiJYcMQoQ5VOzIOEpK/gGpcCIFP1ArYMvmJa2MFqKWuBaIpneRrK\nA3muuq3OpD//I89n\n-----END -----\n" signature:"0E\002!\000\251\261\3409T\340\325\221\\\344\342@!! mK\346S\025\225yI\014`\366H\314ZI\300\247\002 W\243\371k\212\351&\223\273\270?L\335/\177\252p2We\002\252\376\014\037\036\3447\353\226\336\220" > 
2017-10-19 17:22:02.526 UTC [chaincodeCmd] chaincodeInvokeOrQuery -> INFO 00a Chaincode invoke successful. result: status:200 
2017-10-19 17:22:02.526 UTC [main] main -> INFO 00b Exiting.....
===================== Invoke transaction on PEER0 on channel 'mychannel' is successful ===================== 

Installing chaincode on org2/peer3...
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/peers/peer0.org2.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org2MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/users/Admin@org2.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer1.org2.example.com:7051
2017-10-19 17:22:02.628 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:22:02.628 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:22:02.628 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 003 Using default escc
2017-10-19 17:22:02.628 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 004 Using default vscc
2017-10-19 17:22:02.697 UTC [golang-platform] getCodeFromFS -> DEBU 005 getCodeFromFS github.com/hyperledger/fabric/examples/chaincode/go/chaincode_example02
2017-10-19 17:22:02.890 UTC [golang-platform] func1 -> DEBU 006 Discarding GOROOT package fmt
2017-10-19 17:22:02.890 UTC [golang-platform] func1 -> DEBU 007 Discarding provided package github.com/hyperledger/fabric/core/chaincode/shim
2017-10-19 17:22:02.890 UTC [golang-platform] func1 -> DEBU 008 Discarding provided package github.com/hyperledger/fabric/protos/peer
2017-10-19 17:22:02.890 UTC [golang-platform] func1 -> DEBU 009 Discarding GOROOT package strconv
2017-10-19 17:22:02.893 UTC [golang-platform] GetDeploymentPayload -> DEBU 00a done
2017-10-19 17:22:02.898 UTC [msp/identity] Sign -> DEBU 00b Sign: plaintext: 0A86070A5C08031A0C08BABEA3CF0510...5F74FD270000FFFFCEF44F9B002C0000 
2017-10-19 17:22:02.898 UTC [msp/identity] Sign -> DEBU 00c Sign: digest: 82FC608DAD4C39B045146B771F483D3D0FEC697102E0A7AD229380CD7AF1D7BD 
2017-10-19 17:22:02.904 UTC [chaincodeCmd] install -> DEBU 00d Installed remotely response:<status:200 payload:"OK" > 
2017-10-19 17:22:02.904 UTC [main] main -> INFO 00e Exiting.....
===================== Chaincode is installed on remote peer PEER3 ===================== 

Querying chaincode on org2/peer3...
===================== Querying on PEER3 on channel 'mychannel'... ===================== 
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/peers/peer0.org2.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org2MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/users/Admin@org2.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer1.org2.example.com:7051
Attempting to Query PEER3 ...3 secs

2017-10-19 17:22:06.036 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2017-10-19 17:22:06.036 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2017-10-19 17:22:06.036 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 003 Using default escc
2017-10-19 17:22:06.036 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 004 Using default vscc
2017-10-19 17:22:06.037 UTC [msp/identity] Sign -> DEBU 005 Sign: plaintext: 0A90070A6608031A0B08BEBEA3CF0510...6D7963631A0A0A0571756572790A0161 
2017-10-19 17:22:06.037 UTC [msp/identity] Sign -> DEBU 006 Sign: digest: AE1249A7F6E58527AC36E07E25FC5BA7C421D683AB1468E5936DBB7BE7160BE7 
Query Result: 90
2017-10-19 17:22:21.341 UTC [main] main -> INFO 007 Exiting.....
===================== Query on PEER3 on channel 'mychannel' is successful ===================== 

========= All GOOD, BYFN execution completed =========== 


 _____   _   _   ____   
| ____| | \ | | |  _ \  
|  _|   |  \| | | | | | 
| |___  | |\  | | |_| | 
|_____| |_| \_| |____/  


~~~
