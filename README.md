# Jeeves Web Services

## Jeeves Client

jeeves.ermiry.com

## Jeeves Service

#### GET /api/jeeves
**Access:** Public \
**Description:** Jeeves top level route \
**Returns:**
  - 200 on success

#### GET api/jeeves/version
**Access:** Public \
**Description:** Returns jeeves service current version \
**Returns:**
  - 200 and version's json on success

#### GET api/jeeves/auth
**Access:** Private \
**Description:** Used to test if jwt keys work correctly \
**Returns:**
  - 200 on success
  - 401 on failed auth