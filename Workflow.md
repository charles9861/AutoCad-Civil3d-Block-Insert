Here’s how to start a **new script** in **Dynamo for Civil 3D** step-by-step —
I’ll keep it precise so you can follow it without hunting around menus.

---

## 🖥 Starting a New Script in Dynamo for Civil 3D

### **1️⃣ Open Dynamo**

* In **Civil 3D**, go to:

  * **Manage** tab → **Visual Programming** panel → **Dynamo**
    *(⚠️ Not Dynamo Player — that’s for running scripts, not making them.)*

---

### **2️⃣ Start a New Script**

* When Dynamo launches:

  * **Click** `File → New` (or press **Ctrl+N**).
  * You’ll see a **blank canvas** with a grid.

---

### **3️⃣ Set Your Workspace Type**

* In the left library panel:

  * Ensure **Civil 3D nodes** are loaded.
    *(The left sidebar should have categories like **Civil 3D**, **AutoCAD**, **Core**, **Geometry**.)*
  * If you only see **Core** and **Geometry**, close and reopen Dynamo from within Civil 3D — that ensures Civil 3D context.

---

### **4️⃣ Save Immediately**

* Go to **File → Save As** and name your script, e.g., `FencePostPlacer.dyn`.
* Save it somewhere you can find it (e.g., project folder).

---

### **5️⃣ Build Your Script**

* Drag nodes from the **Library** panel onto the canvas.
* Connect them with wires.
* Right-click → **Create Node** to quickly search and place.
* Press **Run** (bottom left) to execute in Civil 3D.

---

💡 **Tip:** While building, keep your Civil 3D drawing open in the background —
some nodes (like *Select Model Element*) will ask you to click on an object in your DWG.

---

If you like, I can give you the **exact sequence of nodes** to drop into this new script so it will start placing fence posts right away. That way, when you start a blank script, you can build it node-by-node without guessing.
