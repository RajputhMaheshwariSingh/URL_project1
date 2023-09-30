# URL_project1 
import pyshorteners

link = input("enter the link : ")
shortener = pyshorteners.Shortener()
shortURL = shortener.tinyurl.short(link)
print(shortURL)
