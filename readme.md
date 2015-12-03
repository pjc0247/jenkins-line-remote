jenkins-line-remote
====
![example](img/example.png)<br>
![jenkins](img/jenkins.png)<br>
<br>
���� �޽����� �̿��� ��Ų�� ���� ���� ȯ�� �����ϱ�.

Noti API
----
���尡 ���۵Ǹ� ���� ��ũ��Ʈ�� __Noti API__�� ���ؼ� ���带 ��û�� ���� ������ �޼����� ���� �� �ֽ��ϴ�.<br>
�� API�� �̿��ϸ� ���� ����, ���� ���� �̿ܿ� �ΰ� �����͸� ���带 ��û�� ����ڿ��� �˷��� �� �ֽ��ϴ�.<br>
�ַ� ���尡 ������ ����� �˸��̳�, ���� �ɸ��� ������ ���, �߰��߰��� �����Ȳ�� �����ϱ� ���ؼ� ����մϴ�.
```
POST /msg/JOB_NAME/BUILD_NUMBER HTTP/1.1

Place Message To Send Here
```

Configure
----
```rb
jenkins_host = "127.0.0.1"
jenkins_user = "pjc"
jenkins_password = "password"

line_user = "pjc0247@pmnxismail.com"
line_password = "djspada"
```

Usage
----

�� �÷��������� �̿��ϱ�
----
�Ѱ��� ���� ������ __jenkins-line-remote__�Ӹ� �ƴ϶� �ٸ� ��ɵ� �ְ��� �� �� ����մϴ�.
* ����

Standalone ���α׷����� �̿��ϱ�
----
�ܼ��� __jenkins-line-remote__���� �̿��ϰ��� �� �� ����մϴ�. �߰����� �ڵ� �ۼ��� �ʿ� ������, ��� ������Ʈ ȯ�濡�� �ٷ� �̿��� �� �ֽ��ϴ�.
```
jenkins_line CONFIG_PATH
```

HEY
----
The source code of this program will not be distributed here cause it contains the LINE protocol implementation codes which is prohibited to upload.
   Please [see](https://github.com/github/dmca/blob/master/2014-06-04-LINE-Corp.md).