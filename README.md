# AS_RANSOMWARE (Go)

Educational Go project that encrypts and decrypts PDF files inside a folder using AES-GCM.

The tool scans the `pdfs` folder, encrypts all `.pdf` files into `.enc` files and deletes the originals.  
The decrypt program restores `.enc` files back to PDF format.

>  This project is for educational purposes only. Do NOT use this code for malicious activity.  

---

## Project Structure

pdfs/    - folder with PDF files  
enc.go   - encrypts files  
dec.go   - decrypts files  
go.mod   - Go module file  

## Usage

1. Create a `pdfs` folder (already included in the project)  
2. Put your PDF files inside the `pdfs` folder  

### Encrypt PDFs
```bash
go run enc.go
```
### Decrypt PDFs
```bash
go run dec.go
```



