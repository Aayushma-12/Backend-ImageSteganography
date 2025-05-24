# Backend - Image Steganography


Flask-based API for image steganography

Provides two endpoints: /encode and /decode

Accepts base64-encoded image input via JSON

Encodes a secret message into an image using a password

Decodes a hidden message from an image using a password

Uses Encode and Decode classes from external modules

Saves temporary images for processing and deletes them after use

Returns base64-encoded image (for encoded) or text (for decoded) in the response
