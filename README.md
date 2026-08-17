<!DOCTYPE html>
<html>
<head>
    <title>oxygen pharmaceutical</title>
</head>
<body>
    <h1>Welcome to oxygen pharmaceutical</h1>
    <p>This is oxygen pharmaceutical website!</p>
</body>
</html>
# Add a contact (location is optional)
python main.py add "John Doe" "09037173270" "Ilaro"

# List all contacts
python main.py list

# Search by name or location
python main.py search "Ilaro"

# Update a contact (any combination of fields)
python main.py update 1 --phone "09030000000" --location "Lagos"

# Delete a contact
python main.py delete 1