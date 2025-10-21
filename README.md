[main.py](https://github.com/user-attachments/files/23011646/main.py)
# main.py
import tkinter as tk
from views import App

# -------------------------------
# Programa Principal
# -------------------------------
if __name__ == "__main__":
    root = tk.Tk()
    app = App(root)
    root.mainloop()
