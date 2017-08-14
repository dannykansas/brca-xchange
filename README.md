# brca-xchange

Combine 23andMe data with BRCA Exchange

This service matches any applicable segements of your 23andMe genomic data with variants described by the BRCA Exchange service (brcaexchange.com).

# Current status 

In order to run the service, you must have a 23andMe Developer API key:

You can run the server via CLI like this:

1. Run the server with your client-id as a parameter
```
python client.py --client-id 5f6d821a3d48c403fd931417f5711ad9
```

2. Enter your client secret at the prompt (or use an environment variable)
3. Navigate to `http://localhost:5000`, by default


# Security Notes

The server is _very barebones_ and not intended to be exposed on any Internet-facing interface.

