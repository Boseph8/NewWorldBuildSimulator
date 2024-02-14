# What to work on
# 1) Setup base GUI
# 2) Setup tables for Perks & Attributes
# 3) Setup Pages for each item
# 4) ... tbd

# Potential Features
# Setup for Head, Gauntlets, Chest, Leggings, footwear (Just to start)
# Within each parent have a category for: Weight class, Attribute, Perk 1, perk 2, perk 3
# Picking perks comes along with Explanation for what they do and what resource to obtain them
# ^ Same thing with attribute
# ?? Maybe resources requried to craft

import customtkinter

class mainframe(customtkinter.CTkFrame):
    def __init__(self,master):
        super().__init__(master)

        
        frame1 = customtkinter.CTkFrame(master)
        frame1.pack(pady=20, padx=20, fill="both", expand=True)

        #Frame1 Button Functionality
        def hframe():
            frame2 = customtkinter.CTkFrame(master)
            frame2.pack(pady=20, padx=20, fill="both", expand=True)

            label2 = customtkinter.CTkLabel(master=frame2, text="Chest Piece", font=("Roboto",36))
            label2.pack(pady=80, padx=12)
        
        def helmet():
            frame1.pack_forget()
            label.pack_forget()
            helmetbutton.pack_forget()
            gauntletbutton.pack_forget()
            chestbutton.pack_forget()
            legsbutton.pack_forget()
            bootsbutton.pack_forget()
            hframe()
            
        def gauntlet():
            pass

        def chest():
            pass

        def legs():
            pass

        def boots():
            pass


        label = customtkinter.CTkLabel(master=frame1, text="New World Build Simulator", font=("Roboto",36))
        label.pack(pady=80, padx=12)

        helmetbutton = customtkinter.CTkButton(master=frame1, text="Helmet", command=helmet)
        helmetbutton.pack(pady=12, padx=12)

        gauntletbutton = customtkinter.CTkButton(master=frame1, text="Gauntlet", command=gauntlet)
        gauntletbutton.pack(pady=12, padx=12)

        chestbutton = customtkinter.CTkButton(master=frame1, text="Chest", command=chest)
        chestbutton.pack(pady=12, padx=12)

        legsbutton = customtkinter.CTkButton(master=frame1, text="Leggings", command=legs)
        legsbutton.pack(pady=12, padx=12)

        bootsbutton = customtkinter.CTkButton(master=frame1, text="Footwear", command=boots)
        bootsbutton.pack(pady=12, padx=12)


class App(customtkinter.CTk):
    def __init__(self):
        super().__init__()

        #App Settings
        customtkinter.set_default_color_theme("green")
        self.geometry("600x600")
        self._set_appearance_mode("dark")

        #App Design
        self.frame = mainframe(self)

       


if __name__ == "__main__":
    app = App()
    app.mainloop() 