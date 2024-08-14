HRMS Employee Create

url - ```http://localhost:8083/egov-hrms/employees/_create?tenantId=pg.gmc```
Request body- 
```
{
    "RequestInfo": {
        "apiId": "Rainmaker",
        "ver": ".01",
        "action": "",
        "did": "1",
        "key": "",
        "msgId": "20170310130900|en_IN",
        "requesterId": "",
        "authToken": "ec6a2db1-c000-4927-af21-f4ce13c1d75f",
        "userInfo": {
            "id": 23287,
            "uuid": "4632c941-cb1e-4b83-b2d4-200022c1a137",
            "userName": "PalashS",
            "name": "Palash S",
            "mobileNumber": "9949032246",
            "emailId": null,
            "type": "EMPLOYEE",
            "roles": [
                {
                    "name": "superuser",
                    "code": "SUPERUSER",
                    "tenantId": "pb.amritsar"
                },
                {
                    "name": "PGR Last Mile Employee",
                    "code": "PGR_LME",
                    "tenantId": "pb.amritsar"
                },
                {
                    "name": "superuser",
                    "code": "SUPERUSER",
                    "tenantId": "pb"
                }
            ],
            "tenantId": "pb.amritsar"
        }
    },
    "Employees": [
        {
            "employeeStatus": "EMPLOYED",
            "user": {
                "name": "ACCOUNTANT STREET LIGHT",
                "mobileNumber": "9898989898",
                "fatherOrHusbandName": "test",
                "gender": "MALE",
                "dob": 1534727942000,
                "correspondenceAddress": "test",
                "roles": [
                    {
                        "name": "EGF Bill Creator",
                        "code": "EGF_BILL_CREATOR",
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Finance Voucher Creator",
                        "code": "EGF_VOUCHER_CREATOR",
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Finance Payment Creator",
                        "code": "EGF_PAYMENT_CREATOR",
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Finance Report View",
                        "code": "EGF_REPORT_VIEW",
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Finance Adminsitrator",
                        "code": "EGF_ADMINISTRATOR",
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Collections Receipt Creator",
                        "code": "COLL_RECEIPT_CREATOR",
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Collections Remitter",
                        "code": "COLL_REMIT_TO_BANK",
                        "tenantId": "pg.gmc"
                    }
                ],
                "tenantId": "pg.gmc"
            },
            "code": "ACCOUNTANT_STREET_LIGHT",
            "employeeType": "PERMANENT",
            "jurisdictions": [
                {
                    "hierarchy": "REVENUE",
                    "boundaryType": "City",
                    "boundary": "pg.gmc",
                    "tenantId": "pg.gmc"
                }
            ],
            "assignments": [
                {
                    "fromDate": 1582137000000,
                    "isCurrentAssignment": true,
                    "toDate": null,
                    "department": "DEPT_1",
                    "designation": "DESIG_58"
                }
            ],
            "serviceHistory": [],
            "education": [],
            "tests": [],
            "tenantId": "pg.gmc"
        }
    ]
}
```

Response body - 
```
{
    "ResponseInfo": {
        "apiId": "Rainmaker",
        "ver": ".01",
        "ts": null,
        "resMsgId": "uief87324",
        "msgId": "20170310130900|en_IN",
        "status": "successful"
    },
    "Employees": [
        {
            "id": 121,
            "uuid": "2e1524cc-951e-496f-b60d-90038c124432",
            "code": "ACCOUNTANT_STREET_LIGHT",
            "employeeStatus": "EMPLOYED",
            "employeeType": "PERMANENT",
            "dateOfAppointment": null,
            "jurisdictions": [
                {
                    "id": "40c8712e-5cfb-4c7e-8d43-7e2cf749c5fc",
                    "hierarchy": "REVENUE",
                    "boundary": "pg.gmc",
                    "boundaryType": "City",
                    "tenantId": "pg.gmc",
                    "auditDetails": {
                        "createdBy": "4632c941-cb1e-4b83-b2d4-200022c1a137",
                        "createdDate": 1723202946476,
                        "lastModifiedBy": null,
                        "lastModifiedDate": null
                    },
                    "isActive": true
                }
            ],
            "assignments": [
                {
                    "id": "013863f2-9491-4a7a-ac9e-30f701e45964",
                    "position": 3,
                    "designation": "DESIG_58",
                    "department": "DEPT_1",
                    "fromDate": 1582137000000,
                    "toDate": null,
                    "govtOrderNumber": null,
                    "tenantid": null,
                    "reportingTo": null,
                    "auditDetails": {
                        "createdBy": "4632c941-cb1e-4b83-b2d4-200022c1a137",
                        "createdDate": 1723202946476,
                        "lastModifiedBy": null,
                        "lastModifiedDate": null
                    },
                    "isHOD": false,
                    "isCurrentAssignment": true
                }
            ],
            "serviceHistory": [],
            "education": [],
            "tests": [],
            "tenantId": "pg.gmc",
            "documents": [],
            "deactivationDetails": [],
            "reactivationDetails": [],
            "auditDetails": {
                "createdBy": "4632c941-cb1e-4b83-b2d4-200022c1a137",
                "createdDate": 1723202946476,
                "lastModifiedBy": null,
                "lastModifiedDate": null
            },
            "reActivateEmployee": null,
            "user": {
                "id": 121,
                "uuid": "2e1524cc-951e-496f-b60d-90038c124432",
                "userName": "ACCOUNTANT_STREET_LIGHT",
                "password": null,
                "salutation": null,
                "name": "ACCOUNTANT STREET LIGHT",
                "gender": "MALE",
                "mobileNumber": "9898989898",
                "emailId": null,
                "altContactNumber": null,
                "pan": null,
                "aadhaarNumber": null,
                "permanentAddress": null,
                "permanentCity": null,
                "permanentPinCode": null,
                "correspondenceCity": null,
                "correspondencePinCode": null,
                "correspondenceAddress": "test",
                "active": true,
                "dob": 1534727942000,
                "pwdExpiryDate": null,
                "locale": null,
                "type": "EMPLOYEE",
                "signature": null,
                "accountLocked": null,
                "roles": [
                    {
                        "name": "EGF Bill Creator",
                        "code": "EGF_BILL_CREATOR",
                        "description": null,
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Finance Voucher Creator",
                        "code": "EGF_VOUCHER_CREATOR",
                        "description": null,
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Finance Payment Creator",
                        "code": "EGF_PAYMENT_CREATOR",
                        "description": null,
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Finance Report View",
                        "code": "EGF_REPORT_VIEW",
                        "description": null,
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Finance Adminsitrator",
                        "code": "EGF_ADMINISTRATOR",
                        "description": null,
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Collections Receipt Creator",
                        "code": "COLL_RECEIPT_CREATOR",
                        "description": null,
                        "tenantId": "pg.gmc"
                    },
                    {
                        "name": "Collections Remitter",
                        "code": "COLL_REMIT_TO_BANK",
                        "description": null,
                        "tenantId": "pg.gmc"
                    }
                ],
                "fatherOrHusbandName": "test",
                "relationship": null,
                "bloodGroup": null,
                "identificationMark": null,
                "photo": null,
                "createdBy": null,
                "createdDate": null,
                "lastModifiedBy": null,
                "lastModifiedDate": null,
                "otpReference": null,
                "tenantId": "pg.gmc"
            },
            "isActive": true
        }
    ]
}
```


FMO User (Checker)

User info- 
```
{
  "id": 122,
  "uuid": "e38f1a24-900d-4624-b3db-d789ae5d7edf",
  "userName": "007",
  "name": "Bimal",
  "mobileNumber": "9953975209",
  "emailId": "bimal.sumatoglobal@gmail.com",
  "locale": null,
  "type": "EMPLOYEE",
  "roles": [
    {
      "name": "Finance Report View",
      "code": "EGF_REPORT_VIEW",
      "tenantId": "pg.gmc"
    },
    {
      "name": "Finance Payment Approver",
      "code": "EGF_PAYMENT_APPROVER",
      "tenantId": "pg.gmc"
    },
    {
      "name": "EGF Bill Approver",
      "code": "EGF_BILL_APPROVER",
      "tenantId": "pg.gmc"
    },
    {
      "name": "Finance Voucher Approver",
      "code": "EGF_VOUCHER_APPROVER",
      "tenantId": "pg.gmc"
    }
  ],
  "active": true,
  "tenantId": "pg.gmc",
  "permanentCity": null
}
```