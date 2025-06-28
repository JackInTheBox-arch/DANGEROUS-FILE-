# WhiteHatLogger

A simple, ethical .NET console app for white hat cybersecurity education.

## 🔍 What It Does

- Captures the **current Windows username**
- Fetches the machine’s **public IP and location** using `ip-api.com`
- Takes a **screenshot of the primary screen**
- Sends all collected data to a **Discord webhook** for demonstration purposes
- Shows visible console prompts to ensure **user awareness and consent**

> ⚠️ This tool is for **educational use only** in environments where you have permission to run it.

---

## 🚀 How to Run

### Option 1: From Visual Studio
1. Open the solution
2. Replace `Program.cs` with `WhiteHatLogger.cs` (if needed)
3. Make sure your `.csproj` targets:
   ```xml
   <TargetFramework>net8.0-windows</TargetFramework>
   <UseWindowsForms>true</UseWindowsForms>
