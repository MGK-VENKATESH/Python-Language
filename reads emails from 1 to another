def read_emails(file_name):
    with open(file_name, 'r') as file:
        emails = file.read().splitlines()
    return emails

def format_emails(emails):
    return ';'.join(emails)

# Specify the file path
file_path = 'D:\\programs\\python\\__pycache__\\emails.txt'  # Update with your file path

# Read the email addresses from the file
email_list = read_emails(file_path)

# Format the email addresses as a string separated by semicolons
formatted_emails = format_emails(email_list)

# Print the formatted email addresses
print(formatted_emails)
