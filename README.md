# webuilder

webapp
  web (protocol:http/https)
    server (ip, host)
      request (type, route & params[all])
        handler{} (request, response)
      response (status, header, content)
    client+ (ip, ua[device])
      user (guest/auth)
      session (online period: heartbeat)
      service (web, api)
      actions (requests)
      route (type, path & params)
      webpage (html)
      content (mime)
  console (admin [default] commands)
    commands (everything can be handled)
    
internet
  web service
    webapp
      server ()
        request
        response
      client+ (user)
      
system
  
web
  server
    
  client
