This is a modified version of https://github.com/Topledger/solana-programs/tree/main/filter-program-transactions made by @Topledger that supports any program address via substream params.
Also the "data" field in the output was changed to bytes rather than bs58::decoded string.

Adjust the manifest params with your list of program addresses each denoted by the program name.  The program name is up to you.

Format
`program_name:program_address;`

Example:
`orca:whirLbMiicVdio4qvUfM5KAg6Ct8VwpYzGff3uctyCc;orca:9W959DqEETiGZocYWCQPaJ6sBmUzgfxXfqGeTEdp3aQP;orca:DjVE6JNiYqPL2QXyCUUh8rNjHrbz9hXHNYt99MQ59qw1`
