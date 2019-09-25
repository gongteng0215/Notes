# PostgreSQL Notes

### Default value

- **Timestamp**: `(('now'::text)::timestamp(0) with time zone)::timestamp without time zone`

- **UUID:**  `upper((gen_random_uuid())::text)`  

  ```asd
  CREATE EXTENSION pgcrypto;
  ```

  

