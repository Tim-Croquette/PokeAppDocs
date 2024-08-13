# Data dictionary

## User account

| Field name    | Type    | Constraints         | Patterns
|---------------|---------|---------------------|-----------------------------------------------------------------------------------------------------------|
| Email         | String  | Unique, not null.   | 1 to 64 chars + "@" + 2 to 252 chars + "." + 2 to 5 chars                                                 |
| Password      | String  | Not null            | 8 to 20 chars, including: <ul><li>At least 1 capitalise</li><li>At least 1 lower case</li><li>At least 1 digit</li><li>At least 1 special char among those: <strong>!?/:-_</strong> </li></ul>                                                                                        |