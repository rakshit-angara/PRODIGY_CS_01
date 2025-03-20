def caesar_cipher(text, shift, encrypt=True):
    result = ""
    if not encrypt:
        shift = -shift  # Reverse shift for decryption

    for char in text:
        if char.isalpha():
            start = ord('A') if char.isupper() else ord('a')
            result += chr((ord(char) - start + shift) % 26 + start)
        else:
            result += char  # Keep non-alphabet characters unchanged

    return result

# User Input
message = input("Enter your message: ")
shift_value = int(input("Enter shift value: "))
choice = input("Do you want to (E)ncrypt or (D)ecrypt? ").strip().lower()

if choice == 'e':
    output = caesar_cipher(message, shift_value, encrypt=True)
    print("Encrypted Message:", output)
elif choice == 'd':
    output = caesar_cipher(message, shift_value, encrypt=False)
    print("Decrypted Message:", output)
else:
    print("Invalid choice! Please enter 'E' for encryption or 'D' for decryption.")
