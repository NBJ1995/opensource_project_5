schema name = nodejsconnect
table name = project
table name = photopath

CREATE TABLE project (
	id	INT NOT NULL primary Key,
    sName VARCHAR(20),
    hit INT
);

CREATE TABLE photopath (
	id	INT NOT NULL primary Key,
    path VARCHAR(40)
);

router ������ main.js���� connection�� �ڱ� �����ͺ��̽��� �°� �������ְ� ���.

������ server.js

���ε��߰��� ���������� photopath ���̺��̶� project ���̺��� ���� ���ɼ��� ����. ������ ��.