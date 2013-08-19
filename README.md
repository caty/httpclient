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
        


License
It's mit style license
