# jlinx-cli

This command line interface allows for reading and writing
[Decentralized IDs (DIDs)](https://w3c.github.io/did-core/) 
persisted and shared using the 
[Hypercore protocol](https://hypercore-protocol.org)


## Setup

```bash
$ npm install -g jlinx-cli
$ jlinx-cli --help
```

### Create a DID

```bash
$ jlinx create
{
  "@context": "https://w3id.org/did/v1",
  "id": "did:hyp:38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28",
  "created": "2022-04-22T22:23:45.151Z",
  "publicKey": [
    {
      "id": "did:hyp:38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28",
      "type": "ed25519",
      "owner": "did:hyp:38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28",
      "publicKeyBase64": "38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28"
    }
  ],
  "updatedAt": "2022-04-22T22:23:45.151Z"
}
```

### Resolve a DID

```bash
$ jlinx resolve 'did:hyp:38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28'
{
  "@context": "https://w3id.org/did/v1",
  "id": "did:hyp:38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28",
  "created": "2022-04-22T22:23:45.151Z",
  "publicKey": [
    {
      "id": "did:hyp:38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28",
      "type": "ed25519",
      "owner": "did:hyp:38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28",
      "publicKeyBase64": "38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28"
    }
  ],
  "updatedAt": "2022-04-22T22:23:45.151Z"
}
```

### Resolve a DID

```bash
$ jlinx resolve 'did:hyp:38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28'
{
  "@context": "https://w3id.org/did/v1",
  "id": "did:hyp:38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28",
  "created": "2022-04-22T22:23:45.151Z",
  "publicKey": [
    {
      "id": "did:hyp:38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28",
      "type": "ed25519",
      "owner": "did:hyp:38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28",
      "publicKeyBase64": "38tk783tfU3ESyYUM4BixeqsGykX3dGsLDW-elEB_28"
    }
  ],
  "updatedAt": "2022-04-22T22:23:45.151Z"
}
```


## TODO

checkout:

- https://oclif.io
- https://github.com/enquirer/enquirer
