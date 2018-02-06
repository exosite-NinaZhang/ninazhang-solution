
## Download File URL
* https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_3M_file
* https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_4M_file
* https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_5M_file
* https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_6M_file
* https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_7M_file
* https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_8M_file
* https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_9M_file

## Create
Create a endpont with below
```{
	"method":"get",
	"path":"/http/get/{size}",
	"content_type":"",
	"script":"local size = request.parameters.size:lower()\nif size == \"3\" then\n  return Http.get({url=\"https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_3M_file\"})\nelseif size == \"4\" then\n  return Http.get({url=\"https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_4M_file\"})\nelseif size == \"5\" then\n  return Http.get({url=\"https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_5M_file\"})\nelseif size == \"6\" then\n  return Http.get({url=\"https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_6M_file\"})\nelseif size == \"7\" then\n  return Http.get({url=\"https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_7M_file\"})\nelseif size == \"8\" then\n  return Http.get({url=\"https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_8M_file\"})\nelseif size == \"9\" then\n  return Http.get({url=\"https://raw.githubusercontent.com/exosite-NinaZhang/qa_fake_data/master/fake_file/temp_10_9M_file\"})\nend"
	}```