def convert_to_fahrenheit(celsius):
    return celsius * 9/5 + 32

# Specify the file paths
input_file = 'D:\\programs\\python\\__pycache__\\temps.txt'  # Update with your input file path
output_file = 'D:\\programs\\python\\__pycache__\\ftemps.txt'  # Update with your output file path

# Read the temperatures from the input file
with open(input_file, 'r') as file:
    temperatures = file.readlines()

# Convert temperatures to Fahrenheit
fahrenheit_temps = [convert_to_fahrenheit(float(temp.strip())) for temp in temperatures]

# Write the Fahrenheit temperatures to the output file
with open(output_file, 'w') as file:
    file.write('\n'.join(str(temp) for temp in fahrenheit_temps))

print("Conversion complete. Fahrenheit temperatures written to 'ftemps.txt'.")


# Read the contents of the output file
with open(output_file, 'r') as file:
    file_contents = file.read()

# Print the contents of the file
print(file_contents)

