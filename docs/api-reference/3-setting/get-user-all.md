---
sidebar_position: 2
---

# GET /v1/users

Let's discover **Docusaurus in less than 5 minutes**.

## Request

Get started by **creating a new site**.

Or **try Docusaurus immediately** with **[docusaurus.new](https://docusaurus.new)**.

### What you'll need

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above:
  - When installing Node.js, you are recommended to check all checkboxes related to dependencies.

## Generate a new site

Generate a new Docusaurus site using the **classic template**.

## ✅ **ส่วนที่ควรมีสำหรับ 1 Endpoint**

| หมวดหมู่            | รายละเอียด                                   |
| ------------------- | -------------------------------------------- |
| ✅ **Summary**      | อธิบาย API สั้น ๆ                            |
| ✅ **HTTP Request** | Method และ Path (`GET /users`)               |
| ✅ **Parameters**   | Query / Path / Header / Body                 |
| ✅ **Request Body** | (ถ้ามี) JSON Schema หรือโครงสร้างตัวอย่าง    |
| ✅ **Response**     | ตัวอย่าง Response 200, 400, 401, 500 เป็นต้น |
| ✅ **Error Code**   | รวมไว้ใน Section แยกหรือในแต่ละ API ได้      |
| ✅ **Examples**     | ตัวอย่าง **curl** หรือ **fetch()** / Axios   |

---

## ✅ **เมนูเพิ่มเติม (แนะนำ)**

| Section            | ใช้ทำอะไร                               |
| ------------------ | --------------------------------------- |
| **Overview**       | อธิบายภาพรวม API, Base URL, Version     |
| **Authentication** | อธิบายวิธีส่ง API Key / Token           |
| **Error Codes**    | รวม Error ทั้งหมดพร้อม code และคำอธิบาย |
| **Changelog**      | สำหรับ version ต่าง ๆ ของ API           |
| **Rate Limits**    | ถ้ามีข้อจำกัด API Rate / Quota          |
| **FAQ**            | คำถามพบบ่อยเกี่ยวกับการเรียกใช้งาน API  |

---

The classic template will automatically be added to your project after you run the command:

```bash
npm init docusaurus@latest my-website classic
```

You can type this command into Command Prompt, Powershell, Terminal, or any other integrated terminal of your code editor.

The command also installs all necessary dependencies you need to run Docusaurus.

## Start your site

Run the development server:

```bash
cd my-website
npm run start
```

The `cd` command changes the directory you're working with. In order to work with your newly created Docusaurus site, you'll need to navigate the terminal there.

The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

Open `docs/intro.md` (this page) and edit some lines: the site **reloads automatically** and displays your changes.
