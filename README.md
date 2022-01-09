text = open("file.csv", "r")
text = ''.join([i for i in text]) \
    .replace("helpinghands.cm", "handsinhands.org")
x = open("employeedata.csv","w")
x.writelines(text)
x.close()
