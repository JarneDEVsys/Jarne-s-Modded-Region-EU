# Jarne's Modded Region EU

A custom **Among Us region server** for the EU.

## 🎮 How to Connect

Follow the steps below to connect to the server.

### 1. Download the Server File

Enter the **server IP** on the region website and click **Download server file**.

> **Important:** The downloaded file must be named exactly:
>
> `regionInfo.json`

Make sure Windows has **not** added a number to the filename, such as:

```text
regionInfo (1).json
regionInfo (2).json
```

If this happens, rename the file back to:

```text
regionInfo.json
```

### 2. Open the Among Us Folder

Press:

**`Win + R`**

Paste the following path into the Run window:

```text
%APPDATA%\..\LocalLow\Innersloth\Among Us
```

Press **Enter** or click **OK**.

### 3. Install the Region File

Copy `regionInfo.json` into the **Among Us** folder that just opened.

If Windows asks whether you want to replace an existing file, confirm the replacement.

### 4. Start Among Us

Open **Among Us** and select:

**Online**

You should now be able to connect to the custom server.

## 🔄 Switching Back to the Official Servers

To return to the original Among Us servers, simply change the **region** using the region selector in the **bottom-right corner** of the Online menu.

## ⚠️ Troubleshooting

### The server does not appear

Make sure:

* `regionInfo.json` is in the correct Among Us folder.
* The filename is exactly `regionInfo.json`.
* Windows has not added `(1)`, `(2)`, etc. to the filename.
* You have restarted Among Us after installing the file.
* You selected **Online** after launching the game.

### The custom region disappeared

Check that the `regionInfo.json` file still exists in:

```text
%APPDATA%\..\LocalLow\Innersloth\Among Us
```

If necessary, download the server file again and replace the existing file.

## 📁 File Structure

Your Among Us folder should contain the region file:

```text
Among Us/
└── regionInfo.json
```

## 📜 Disclaimer

This is a **community/private server configuration** for Among Us. It is not an official Innersloth server.

---

**Jarne's Modded Region EU**
Enjoy playing! 🚀
