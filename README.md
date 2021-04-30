# webuilder

webapp
  web (protocol:http/https)
    server (ip, host)
      request (type, route & params[all])
        handler (request, response)
      response (status, header, content)
    client+ (ip, ua[device])
      user (auth)
      
  console (admin commands)
    