# Script Name

Generate firebase identity token to use firebase REST services using firebase service accounts. For instance, getting oAuth token from firebase requires identity token to be passed.

### Prerequisites

- [link Create service accounts](https://console.cloud.google.com/projectselector2/iam-admin/serviceaccounts)
- [link Gather require information](https://developers.google.com/identity/protocols/oauth2/service-account#httprest)
- [link Update script](https://github.com/queendevelopers/firebase-identity-token-generator/blob/master/firebase-identity-token-generator)

Ensure you have one of the following tools installed:

- awk
- jd
- sed


### Installing

You can download the script using the following command:

### Using Curl
```bash
curl -O https://github.com/queendevelopers/firebase-identity-token-generator/blob/master/firebase-identity-token-generator
```

### Using Wget
```bash
wget https://github.com/queendevelopers/firebase-identity-token-generator/blob/master/firebase-identity-token-generator
```

### Permission & Running script
```bash
chmod +x firebase-identity-token-generator
./firebase-identity-token-generator
```

