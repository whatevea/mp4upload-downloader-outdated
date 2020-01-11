Import mp4 object and make instance of the class passing the mp4 upload url as attribute,
run the method of .press2() which will return the byte content of .mp4 file.

s2=mp4("https://www.mp4upload.com/35uvhzb69ynx")
open(str(s2.filename)+".mp4",'wb').write(s2.press2())
