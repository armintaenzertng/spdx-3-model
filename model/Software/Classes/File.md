SPDX-License-Identifier: Community-Spec-1.0

# File

## Description

TODO This is about the File class.

## Metadata

- name: File
- SubclassOf: Core:Artifact

## Properties

- contentIdentifier
  - type: xsd:anyURI
  - minCount: 0
  - maxCount: 1
- filePurpose
  - type: SoftwarePurpose
  - minCount: 0
- contentType
  - type: MediaType
  - minCount: 0
  - maxCount: 1

