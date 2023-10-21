# certutil

> सर्टीफिकेट सूचना को प्रबंधित और विन्यसित करने के लिए एक टूल।
> अधिक जानकारी: <https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/certutil>.

- विन्यास सूचना या फ़ाइलों को डंप करें:

`certutil {{फ़ाइलनाम}}`

- एक फ़ाइल को हेक्साडेसिमल में एनकोड करें:

`certutil -encodehex {{इनपुट_फ़ाइल/का/पथ}} {{आउटपुट_फ़ाइल/का/पथ}}`

- एक फ़ाइल को बेस64 में एनकोड करें:

`certutil -encode {{इनपुट_फ़ाइल/का/पथ}} {{आउटपुट_फ़ाइल/का/पथ}}`

- बेस64-एनकोड फ़ाइल को डीकोड करें:

`certutil -decode {{इनपुट_फ़ाइल/का/पथ}} {{आउटपुट_फ़ाइल/का/पथ}}`

- एक फ़ाइल पर एक आपातकालिक हैश उत्पन्न करें और प्रदर्शित करें:

`certutil -hashfile {{इनपुट_फ़ाइल/का/पथ}} {{md2|md4|md5|sha1|sha256|sha384|sha512}}`