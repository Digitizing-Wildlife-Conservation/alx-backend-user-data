0x00. Personal data Back-end Authentification Cohort

This project involves tasks designed to help users learn to protect personal data.

Tasks Completed:

Regex-ing: Implemented a function called filter_datum in filtered_logger.py. This function obfuscates specified fields in a log message using a regex. It takes arguments for the fields to be obfuscated, the redaction string, the message, and the separator character. The function is concise, under 5 lines, and uses re.sub for substitution.

Log Formatter: Updated filtered_logger.py to include a RedactingFormatter class that inherits from logging.Formatter. This class replaces sensitive information in log records with a redaction string. The class defines a format and a separator for the log messages and includes an overridden format method for the redaction process.

                                                                           -Happy Coding-`
