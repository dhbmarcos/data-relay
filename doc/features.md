# Resume

- Views based in collection of ontological path defined by user;
- Assign ontological paths to files;
- Views signed by agent;
- Agent based in asymmetric keys (RSA 2048 key pair);
- Agent identification based in pubic key only;
- Prevent data duplication: using files named by your own hash (SHA-3 224);
- Data corruption verification: using files named by your own hash (SHA-3 224);
- Native encryption: encrypt, decrypt (AES 256 bits over RSA 2048 bits), sign and verify (RSA 2048 bits) data;
- Network nodes defined by shared node list.

## Legend

- The diagrams is conform SysML standard.
- Sketched diagrams indicate view not implemented.
- The thicker flow lines (double thickness) indicate preferred flow.
- The dashed flow lines indicate dependency (depends on).
- The blocks with shadow and thicker edges (double thickness) indicate input/output interfaces.
- The blocks even thicker edges (quadruple thickness) indicate default activity or link to other diagram.

# Use Cases

## Main Features
![Main Use Case](data-relay-uc-main.svg)

## Data Deletion Prevention
![Main Use Case](data-relay-uc-data-deletion-prevention.svg)

# Activities

## Agent Features

### Create Agent
![Create Agent](data-relay-act-create-agent.svg)

### Import Agent
![Import Agent](data-relay-act-import-agent.svg)

## Data Features

### Import Data
![Import Data](data-relay-act-import-data.svg)

### Create Data
![Create Data](data-relay-act-create-data.svg)

### Delete Data
![Encrypt](data-relay-act-delete-data.svg)

### Protect Data
![Identify](data-relay-act-protect-data.svg)

## Internal Features

### Encrypt
![Encrypt](data-relay-act-encrypt.svg)

### Decrypt
![Decrypt](data-relay-act-decrypt.svg)

### Identify
![Identify](data-relay-act-identify.svg)

### Sign
![Sign](data-relay-act-sign.svg)
