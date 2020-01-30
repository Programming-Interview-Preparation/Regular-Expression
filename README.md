# Regular-Expression
Regular Expression to Check

| Expression  | Description |
| ------------- | ------------- |
| "^(?=.*[A-Za-z])(?=.*\d)[A-Za-z\d]{8,}$"  | Minimum eight characters, at least one letter and one number |
| "^(?=.*[A-Za-z])(?=.*\d)(?=.*[@$!%*#?&])[A-Za-z\d@$!%*#?&]{8,}$"  | Minimum eight characters, at least one letter, one number and one special character  |
|"^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)[a-zA-Z\d]{8,}$"|Minimum eight characters, at least one uppercase letter, one lowercase letter and one number|
|"^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{8,}$"|Minimum eight characters, at least one uppercase letter, one lowercase letter, one number and one special character |
|"^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{8,10}$"|Minimum eight and maximum 10 characters, at least one uppercase letter, one lowercase letter, one number and one special character|
|"^(?=.*[\p{Ll}])(?=.*[\p{Lu}])(?=.*\d)(?=.*[$@$!%*?&])[\p{Ll}\p{Lu}\d$@$!%*?&]{6,}"|Minimum 6 characters at least 1 Uppercase Alphabet, 1 Lowercase Alphabet, 1 Number and 1 Special Character|
|"^(?=.*[A-Za-z])(?=.*\d)[A-Za-z\d!$%@#£€*?&]{8,}$"|Minimum 8 characters at least 1 Alphabet and 1 Number with Optional Special Chars|
|||
