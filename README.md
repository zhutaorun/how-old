# how-old
now project limite jpg size less than 3M;
On MI moblie Phone,Unable to decode stream: java.lang.NullPointerException

Mobile devices typically have constrained system resources.
Android devices can have as little as 16MB of memory available to a single application.

zhutaorun@163.com

安卓的图片裁剪和camera 调用系统拍照返回null
http://www.linuxidc.com/Linux/2012-11/73940.htm
http://www.linuxidc.com/Linux/2012-11/73939.htm
http://blog.csdn.net/zimo2013/article/details/16916279

API地址
http://www.faceplusplus.com.cn/

1.选择照片
intentzxghj

2.人脸识别

{
    "face": [
        {
            "position": {
                "mouth_right": {
                    "y": 55.840667,
                    "x": 61.027713
                },
                "mouth_left": {
                    "y": 57.680167,
                    "x": 33.448915
                },
                "center": {
                    "y": 40.583333,
                    "x": 40.651085
                },
                "height": 56.5,
                "width": 56.594324,
                "nose": {
                    "y": 43.897833,
                    "x": 42.125376
                },
                "eye_left": {
                    "y": 28.8445,
                    "x": 27.810851
                },
                "eye_right": {
                    "y": 27.381667,
                    "x": 53.964274
                }
            },
            "attribute": {
                "race": {
                    "value": "White",
                    "confidence": 70.83749999999999
                },
                "gender": {
                    "value": "Female",
                    "confidence": 94.8717
                },
                "smiling": {
                    "value": 28.4889
                },
                "age": {
                    "value": 16,
                    "range": 5
                }
            },
            "tag": "",
            "face_id": "d0cdb9d2a39f8f9570b23c54020bab01"
        }
    ],
    "session_id": "f0707e3d1d0645809daa970bcdff71f4",
    "img_height": 621,
    "img_width": 620,
    "img_id": "91a914730677a6f746b95af547420414",
    "url": null,
    "response_code": 200
}
