# File Packer & Unpacker with Encryption 

# Technology: Java Programming

# Project Overview:
This project is a Java-based file utility tool that provides functionality for packing 
multiple files into a single archive and unpacking them back with all metadata 
preserved.  
To enhance security, the packed file is encrypted, and only authorized users can decrypt & 
extract the data.  

# Key Features :
• File Packing 
  ◦ Combines multiple regular files into a single archive file. 
  ◦ Stores metadata (file name, size, timestamp) along with file content. 
• File Unpacking 
  ◦ Extracts individual files from the packed archive. 
• Data Security 
  ◦ Restores all original metadata and file structure. 
  ◦ Built-in encryption and decryption to protect packed files. 
• Cross-platform 
  ◦ Runs seamlessly on any system with a Java Runtime Environment (JRE). 

# Learning Outcomes 
• Practical experience with Java I/O Streams and File Handling APIs. 
• Implementation of metadata management during file operations. 
• Strong understanding of encryption/decryption techniques in Java. 
• Insight into archiving and compression utilities (similar to ZIP/TAR). 

# Example Usage (Console Flow):
# Packing files 
$ java FilePacker Demo MarvellousPack.txt 

# Unpacking files 
$ java FileUnpacker MarvellousPack.txt 
