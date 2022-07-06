# Flow-3
 Este repositorio contiene el Flow 3 del curso IoT
 
[
    {
        "id": "c693b035d0aa4065",
        "type": "tab",
        "label": "Flow 2",
        "disabled": false,
        "info": "",
        "env": []
    },
    {
        "id": "a994a0abc6767a3a",
        "type": "inject",
        "z": "c693b035d0aa4065",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 140,
        "y": 100,
        "wires": [
            [
                "0d1008258fde0ca0",
                "a88aedb11f85dffe"
            ]
        ]
    },
    {
        "id": "0d1008258fde0ca0",
        "type": "function",
        "z": "c693b035d0aa4065",
        "name": "",
        "func": "\nreturn msg;",
        "outputs": 1,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 340,
        "y": 80,
        "wires": [
            [
                "983e2aae91b5cef5",
                "b2a8107c5552fbea"
            ]
        ]
    },
    {
        "id": "a88aedb11f85dffe",
        "type": "debug",
        "z": "c693b035d0aa4065",
        "name": "",
        "active": false,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": " ",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 330,
        "y": 140,
        "wires": []
    },
    {
        "id": "983e2aae91b5cef5",
        "type": "debug",
        "z": "c693b035d0aa4065",
        "name": "",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": " ",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 550,
        "y": 100,
        "wires": []
    },
    {
        "id": "b2a8107c5552fbea",
        "type": "debug",
        "z": "c693b035d0aa4065",
        "name": "",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "g9",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 560,
        "y": 160,
        "wires": []
    }
]
