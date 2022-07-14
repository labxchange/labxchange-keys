LabXchange Opaque Keys
======================

This registers the custom OpaqueKeys used by LabXchange, e.g. for Pathways and their children.

## Testing

```
# 1. Clone the repo
git clone https://github.com/open-craft/labxchange-keys

# 2. Create and activate a virtualenv
python3 -m venv venv
source venv/bin/activate

# 3. Install the requirements
cd labxchange-keys
make requirements

# 4. Check quality and run the tests
make validate
```
