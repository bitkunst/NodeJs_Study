컴퓨터는 이미지 파일을 어떻게 저장하고 있는가?
이미지 -> 텍스트

이미지 파일도 결국에는 텍스트 파일이다.
브라우저의 자체 기능만으로도 이미지 파일을 올리면 텍스트로 바꿔서 body영역에 실어서 보내는 것 까지는 가능
웹 서버에서 외계어같은 코드를 해석하는 것이 라이브러리를 통해서 가능 (12분, 13분?)

==================================================================================

프론트 - 웹 서버에게 파일을 요청 보내는 행위

백 - 클라이언트에서 보낸 request body 영역을 해석하는 행위를 만들어야 한다.

npm install multer --save


# payload
-----------------------------2295777367200267933439787201
Content-Disposition: form-data; name="subject"

asdf
-----------------------------2295777367200267933439787201
Content-Disposition: form-data; name="upload"; filename=""
Content-Type: application/octet-stream

asdfgsklnfsklnvsinvisisisd  <= 외계어들이 들어감;


-----------------------------2295777367200267933439787201--


비동기 형태로도 파일업로드 가능.
