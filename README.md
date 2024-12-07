# 🚀 HttpGet Manager
Simple script that has many features that allows you to manage HttpGet request's

## 🖥 Getting Started!

*HttpGet Manager works best when put inside your autoexecute folder.*

*Remember to edit the configuration first!*

### 👨‍💻 Default Configuration

```
local Software = {
  ["EnableHTTPGET"] = true,
  ["DebugMode"] = true,
  ["RedirectionURL"] = "https://www.webpagetest.org/blank.html",
  ["IPManager"] = {
    ["EnableAntiIPLog"] = true,
    ["BlockIPTransfering"] = true,
    ["IP"] = "",
    ["FakeIP"] = "110.151.93.130",
    ["KnownIPLOGURL"] = {
      ""
    },
    ["KeywordURL"] = {
      "ip",
      "geolocation"
    }
  },
  ["UrlManager"] = {
    ["EnableBlacklistedURL"] = false,
    ["BlacklistedURL"] = {
      ""
    },
    ["EnableWhitelistedURL"] = false,
    ["WhitelistedURL"] = {
      ""
    },
  },
  ["ProtocolManager"] = {
    ["AllowHttps"] = true,
    ["AllowHttp"] = true,
  },
  ["DomainManager"] = {
    ["EnableBlacklistedDomains"] = true,
    ["BlacklistedDOMAIN"] = {
      "ipify"
    },
    ["EnableWhitelistedDomains"] = true,
    ["WhitelistedDOMAIN"] = {
      "pastebin",
      "github",
      "githubusercontent"
    }
  },
  ["TLDManager"] = {
    ["EnableBlacklistedTLD"] = false,
    ["BlacklistedTLD"] = {
      ""
    },
    ["EnableWhitelistedTLD"] = false,
    ["WhitelistedTLD"] = {
      ""
    }
  },
  ["Secruity"] = {
    ["PreventBypassClonefunction"] = true,
    ["PreventBypassHookfunction"] = true,
    ["PreventProtocolBypass"] = true
  }
}
```

### 📚 Understanding it!
