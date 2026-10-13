# Private Banking MCP Production — Privacy notice

Last updated: 2026-10-13. Operator: Arthurofox.

This application is operated by its owner solely to retrieve that owner's personal bank-account information. It is not available to the public or to other account holders.

Contact for questions, access requests or deletion: **arthurofox@gmail.com**.

With the owner's explicit consent, the application retrieves account identifiers and references, balances, transaction dates, amounts, currencies, bank descriptions and counterparties through Enable Banking's account-information API. Banking authentication is completed on the bank/provider pages; the application does not request or store online-banking passwords, PINs or one-time authentication codes.

Enable Banking mediates account access under its own end-user terms and privacy information, presented during the consent flow. Its API access requires a protected application signing key and consent-session identifiers; these are kept separately from the read-only MCP process.

During the initial real-account test, account information and session state are stored locally on the owner's PC, in encrypted files with separately protected keys. An authorized read-only MCP client can receive selected account and transaction results. If that client sends results to an external AI provider, that provider's separate privacy and retention rules apply. The owner controls which client is connected and which data is requested.

The application does not sell financial information, provide advertising or include analytics/classification services. Bank descriptions are preserved as received. The current integration contains no payment-initiation feature.

Financial records are retained until the owner deletes them or the application. Revoking consent stops future bank access but does not automatically delete previously synchronized records or backups. The owner can revoke consent through the bank/provider and delete local data, keys and backups. Any future server deployment, external backup destination or other change in processing must be reflected in this notice before use.

General references: https://enablebanking.com/privacy and https://tilisy.enablebanking.com/terms.
