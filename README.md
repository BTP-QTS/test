
# Hyperledger Fabric test code

A brief description of what this project does and who it's for
Microfab can be configured by specifying the MICROFAB_CONFIG environment variable. For example, to start Microfab with different organizations using Docker, run the following commands:
## Setup details
`
export MICROFAB_CONFIG='{
    "endorsing_organizations":[
        {
            "name": "SampleOrg"
        }
    ],
    "channels":[
        {
            "name": "mychannel",
            "endorsing_organizations":[
                "SampleOrg"
            ]
        }
    ]
}'
`


`
docker run -p 8080:8080 -e MICROFAB_CONFIG ibmcom/ibp-microfab
`


## System Requirements

*  NodeJS
*  IBM Blockchain Platform : VS Code Extension
*  Docker


SUSEyUIHLmnxckC5pLBkbpTKKQzoZ940WnfTaLJQ+302VX26VmNn6OxLjFlMcvTzl/TBNrwoFZqwM5apgw9wmw==
