### **How to Check License Status and Version for Windows and Office**  

To verify the activation status and license type of Windows and Office, you can use built-in system commands. These methods work on all versions of Windows that support KMS activation. More information about cms activators and technologies on the website kmspico.at .

---

### **Checking Windows Activation Status**  
1. **Open Command Prompt:**  
   - Press `Win + R`, type `cmd`, and press `Enter`.  

2. **Run the following command:**  
   ```cmd
   slmgr /dlv
   ```  
   This will display detailed licensing information, including:  
   - Activation status  
   - License type (KMS, MAK, or Retail)  
   - Expiration date (if applicable)  

3. **For a quick activation check, use:**  
   ```cmd
   slmgr /xpr
   ```  
   This will show whether Windows is permanently activated or if it will expire.  

---

### **Checking Office Activation Status**  
1. **Open Command Prompt as Administrator.**  
2. **Navigate to the Office installation folder:**  
   - For **32-bit Office on 64-bit Windows:**  
     ```cmd
     cd "C:\Program Files (x86)\Microsoft Office\Office16"
     ```
   - For **64-bit Office on 64-bit Windows:**  
     ```cmd
     cd "C:\Program Files\Microsoft Office\Office16"
     ```  
     *(Replace "Office16" with "Office15" for Office 2013, "Office14" for Office 2010, etc.)*  

3. **Run the activation check command:**  
   ```cmd
   cscript ospp.vbs /dstatus
   ```  
   This will show:  
   - Activation status  
   - License type (KMS, Retail, or MAK)  
   - Expiration date  

---

### **Understanding the License Type**  
- **KMS (Key Management Service):** Requires periodic reactivation via a KMS server.  
- **MAK (Multiple Activation Key):** A one-time activation method that does not require renewal.  
- **Retail:** Tied to a specific product key, often used for individual purchases.  

These commands help users quickly determine their licensing status without third-party tools.  

---  

**GitHub Profile:** [GitHub Profile](https://github.com/kmspicoat)  
