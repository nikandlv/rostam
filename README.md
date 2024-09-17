# Rostam DNS Manager

Rostam is a tiny application to change name servers in linux devices.

Currently it is written to set anti sanction dns services.

- Shecan DNS
- 403 DNS

# Setup

## Step 1

Download the release file or build it your self

```bash
cargo build --release
```

## Step 2

Move it to the path of your choice

```bash
sudo mv ./target/release/rostam /usr/bin
```

## Step 3

Run it

```bash
rostam
```
