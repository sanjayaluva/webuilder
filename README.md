# webuilder

webapp
  web (protocol:http/https)
    server (ip, host)
      request (type, route & params[all])
        handler{} (request, response)
      response (status, header, content)
    client+ (ip, ua[device])
      user (guest/auth)
      session (visiting period: heartbeat)
      service (web, api)
      actions (re)
      route (type, path & params)
      webpage (html)
      content (mime)
  console (admin [default] commands)
    commands (everything can be handled)
    
