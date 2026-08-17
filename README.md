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
python main.py add "AJIBOLA BILAL" "09037173270" "Ilaro"

# List all contacts
python main.py list

# Search by name or location
python main.py search "Ilaro"
# Add a medication (name, dose, quantity)
python main.py add "Amoxicilline BGR" "1g" 14

# List all medications
python main.py list

# Search by name
python main.py search "Amox"

# Update a medication (any combination of fields)
python main.py update 1 --quantity 10

# Delete a medication
python main.py delete 1

