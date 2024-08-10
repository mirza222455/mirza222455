meme_dict = {
            "CRINGE": "Garip yada utanılabilecek birşey",
            "LOL":"Komik bir şeye verilen cevap",    
            "GHOSTING":"Yokmuş gibi davramak"
}


meme = input("Anladığınız kelimeleri büyük harflerle yazın")

if word in meme_dict.keys():
    print(meme_dict[word])

else:
    print ("Bu kelime sözlüğümüzde yok")
--->
