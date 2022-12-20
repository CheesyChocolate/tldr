# cipher

> NTFS டிரைவ்களில் உள்ள கோப்புகளை குறியாக்கம் அல்லது மறைகுறியாக்கம் செய்யவும்.
> மேலும் விவரத்திற்கு: <https://learn.microsoft.com/windows-server/administration/windows-commands/cipher>.

- ஒரு குறிப்பிட்ட மறைகுறியாக்கப்பட்ட கோப்பு அல்லது கோப்பகம் பற்றிய தகவலைக் காண்பி:

`cipher /c:{{பாதை/டு/கோப்பு_அல்லது_அடைவு}}`

- ஒரு கோப்பு அல்லது கோப்பகத்தை குறியாக்கு (கோப்பகத்தில் பின்னர் சேர்க்கப்பட்ட கோப்புகளும் கோப்பகம் குறிக்கப்பட்டதால் குறியாக்கம் செய்யப்படுகின்றன):

`cipher /e:{{பாதை/டு/கோப்பு_அல்லது_அடைவு}}`

- ஒரு கோப்பு அல்லது கோப்பகத்தை மறைகுறியாக்கவும்:

`cipher /d:{{பாதை/டு/கோப்பு_அல்லது_அடைவு}}`

- ஒரு கோப்பு அல்லது கோப்பகத்தை பாதுகாப்பாக அகற்றவும்:

`cipher /w:{{பாதை/டு/கோப்பு_அல்லது_அடைவு}}`