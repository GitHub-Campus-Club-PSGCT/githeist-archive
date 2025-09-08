# githeist-archive

# Redacted Document Viewer

Redacted documents can be **unredacted** using a **redaction key**. 

---

## How It Works

1. **Download the File**
   Save the redacted document locally.

2. **Find the Redaction Key**
   Look near the redacted section for the encrypted key (Base64-encoded hex string).

3. **Decode the Redaction Key**

   * **Manual**:

     Convert Hex → Decimal → ASCII characters

   * **Example Tool**: [CyberChef](https://gchq.github.io/CyberChef/)

     * Use `From Hex` 

4. **Unredact the File**
   Enter the decoded key in the viewer to reveal the hidden content.

> Decoded key works **only for one file**.

---

