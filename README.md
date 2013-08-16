httpclient
==========

cocos2d-x httpclient post file multipart/form-data

Usage:

        CCHttpRequest* request = new CCHttpRequest();
        request->setUrl("http://hostname/upload");
        request->setRequestType(CCHttpRequest::kHttpPostFile);
        request->setFileData((const unsigned char *)postData, size, filename );
        request->setResponseCallback(this, httpresponse_selector(::onHttpRequestCompleted));
        CCHttpClient::getInstance()->send(request);
        request->release();
        


License (mit style license)

Copyright (c) 2013 cacaty at google mail

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
