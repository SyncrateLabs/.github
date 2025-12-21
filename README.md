# Syncrate

**A decentralized routing layer for tokenized Real-World Assets.**
Syncrate provides an infrastructure layer that enables assets issers and investors to move capital across different chains and assets classes without breaking compliance and security.  

> # 🚧 Status
> 
> Syncrate is currently under active development.
> This repository will be updated as milestones are completed. 
> Follow us for updates!

# What Syncrate Does

- Checks the user's KYC and allowlist status of the source and destination assets based on individual issuer attestations and KYC check mechanism.

- Redeems the source asset at the issuers redemption gateway (the users gets USDC or other stable-settlment token depending on the issuer's structure)

- Bridges the USDC via Circle's CCTP

- Sends a mint/issuance request to the destination asset's issuer. The destination asset is then minted to the user's wallet - no wrapped tokens, no synthetic pools. 


# 📄 License

MIT License. 
