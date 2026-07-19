user-controller

GET
/api/users/{id}
Get user by ID


PUT
/api/users/{id}
Update user by ID



DELETE
/api/users/{id}
Delete user by ID



PUT
/api/users/{id}/status
Update user status



GET
/api/users/profile
Get current user profile



PUT
/api/users/profile
Update current user profile



GET
/api/users/patients
Get all patients



GET
/api/users/doctors
Get all doctors



GET
/api/users/doctors/public
Get all doctors for public view



GET
/api/users/all
Get all users


medical-record-controller


GET
/api/medical-records/{id}



PUT
/api/medical-records/{id}



DELETE
/api/medical-records/{id}



POST
/api/medical-records



GET
/api/medical-records/patient/{patientId}



GET
/api/medical-records/patient/{patientId}/doctor/{doctorId}



GET
/api/medical-records/my



GET
/api/medical-records/my-patients



GET
/api/medical-records/doctor/{doctorId}



GET
/api/medical-records/date



GET
/api/medical-records/all


feedback-controller


GET
/api/feedback/{id}



PUT
/api/feedback/{id}



DELETE
/api/feedback/{id}



POST
/api/feedback



GET
/api/feedback/rating



GET
/api/feedback/patient/{patientId}



GET
/api/feedback/patient/{patientId}/doctor/{doctorId}



GET
/api/feedback/my



GET
/api/feedback/my-patients



GET
/api/feedback/general



GET
/api/feedback/doctor/{doctorId}



GET
/api/feedback/doctor-specific



GET
/api/feedback/all



GET
/api/feedback/all/public


doctor-schedule-controller


GET
/api/doctor-schedules/{id}



PUT
/api/doctor-schedules/{id}



DELETE
/api/doctor-schedules/{id}



POST
/api/doctor-schedules



POST
/api/doctor-schedules/{scheduleId}/book



GET
/api/doctor-schedules/my-schedules



GET
/api/doctor-schedules/doctor/{doctorId}



GET
/api/doctor-schedules/available



GET
/api/doctor-schedules/all



DELETE
/api/doctor-schedules/my-schedules/{id}


department-controller


GET
/api/departments/{id}



PUT
/api/departments/{id}



DELETE
/api/departments/{id}



GET
/api/departments



POST
/api/departments



GET
/api/departments/public

appointment-controller


GET
/api/appointments/{id}



PUT
/api/appointments/{id}



DELETE
/api/appointments/{id}



PUT
/api/appointments/{id}/status



PUT
/api/appointments/{id}/complete



PUT
/api/appointments/{id}/cancel



POST
/api/appointments



GET
/api/appointments/status/{status}



GET
/api/appointments/patient/{patientId}



GET
/api/appointments/my



GET
/api/appointments/my-patients



GET
/api/appointments/doctor/{doctorId}



GET
/api/appointments/date



GET
/api/appointments/all


auth-controller


POST
/api/auth/verify-signup-otp


POST
/api/auth/test-token


POST
/api/auth/test-otp


POST
/api/auth/test-otp-generation


POST
/api/auth/signup


POST
/api/auth/signin


POST
/api/auth/send-signup-otp


POST
/api/auth/reset-password


POST
/api/auth/forgot-password


POST
/api/auth/admin/create-user



GET
/api/auth/health