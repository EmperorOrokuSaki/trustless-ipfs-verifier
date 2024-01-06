# Trustless IPFS Verifier Extension

This extension aims to identify the correct content for NFA websites by fetching the IPFS CID from a trustless node and comparing its hash against the loaded browser body data.

## What remains

[] Implement the mechanism for fetching the CID from a trustless Helia gateway.
[] Apply DeclarativeNetRequest blockade on all NFA domains.
[] Connect it to NFA API endpoints to fetch all NFA domains and their latest IPFS CID.
