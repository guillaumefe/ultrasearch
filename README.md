## You can use this JSON configuration file
*You may want to do your own*

```
[
  {
    "category": "General Information",
    "dorks": [
      {
        "label": "Exact occurrences of \"{target}\"",
        "value": "+(\"{target}\" AND \"{target}\")"
      },
      {
        "label": "Results containing \"{target}\"",
        "value": "+\"{target}\""
      }
    ]
  },
  {
    "category": "Social Media",
    "dorks": [
      {
        "label": "Results on Facebook",
        "value": "site:facebook.com \"{target}\""
      },
      {
        "label": "Results on Twitter",
        "value": "site:twitter.com \"{target}\""
      },
      {
        "label": "Results on LinkedIn",
        "value": "site:linkedin.com \"{target}\""
      },
      {
        "label": "Results on Instagram",
        "value": "site:instagram.com \"{target}\""
      },
      {
        "label": "Results on VK",
        "value": "site:vk.com \"{target}\""
      },
      {
        "label": "Results on Weibo",
        "value": "site:weibo.com \"{target}\""
      },
      {
        "label": "Results on Tumblr",
        "value": "site:tumblr.com \"{target}\""
      },
      {
        "label": "Results on Snapchat",
        "value": "site:snapchat.com \"{target}\""
      },
      {
        "label": "Results on Discord",
        "value": "site:discord.com \"{target}\""
      },
      {
        "label": "Results on Telegram",
        "value": "site:telegram.org \"{target}\""
      },
      {
        "label": "Results on Quora",
        "value": "site:quora.com \"{target}\""
      },
      {
        "label": "Results on Medium",
        "value": "site:medium.com \"{target}\""
      },
      {
        "label": "Results on Clubhouse",
        "value": "site:clubhouse.com \"{target}\""
      },
      {
        "label": "Results on Threads",
        "value": "site:threads.net \"{target}\""
      },
      {
        "label": "Results on Reddit",
        "value": "site:reddit.com \"{target}\""
      },
      {
        "label": "Results on Pinterest",
        "value": "site:pinterest.com \"{target}\""
      },
      {
        "label": "Results on TikTok",
        "value": "site:tiktok.com \"{target}\""
      },
      {
        "label": "Results on YouTube",
        "value": "site:youtube.com \"{target}\""
      }
    ]
  },
  {
    "category": "Vulnerabilities and Security Flaws",
    "dorks": [
      {
        "label": "Vulnerabilities reported on HackerOne",
        "value": "site:hackerone.com \"{target}\""
      },
      {
        "label": "Vulnerabilities reported on BugCrowd",
        "value": "site:bugcrowd.com \"{target}\""
      },
      {
        "label": "Vulnerabilities reported on OpenBugBounty",
        "value": "site:openbugbounty.org \"{target}\""
      },
      {
        "label": "SQL Injections",
        "value": "\"{target}\" \"sql injection\""
      },
      {
        "label": "XSS",
        "value": "\"{target}\" \"xss\""
      },
      {
        "label": "Remote Code Execution",
        "value": "\"{target}\" \"rce\""
      },
      {
        "label": "CSRF",
        "value": "\"{target}\" \"csrf\""
      },
      {
        "label": "Directory Traversal",
        "value": "\"{target}\" \"directory traversal\""
      },
      {
        "label": "Vulnerable Deserialization",
        "value": "\"{target}\" \"deserialization vulnerability\""
      },
      {
        "label": "Exploits on Exploit-DB",
        "value": "site:exploit-db.com \"{target}\""
      },
      {
        "label": "Data leaks on Pastebin",
        "value": "site:pastebin.com \"{target}\" \"password\" OR \"leak\""
      },
      {
        "label": "CVE on NVD",
        "value": "site:nvd.nist.gov \"{target}\""
      },
      {
        "label": "Shodan Analysis",
        "value": "site:shodan.io \"{target}\""
      },
      {
        "label": "Censys Analysis",
        "value": "site:censys.io \"{target}\""
      },
      {
        "label": "Exposed configuration files",
        "value": "inurl:{target} filetype:env OR filetype:cfg"
      },
      {
        "label": "Exposed backup files",
        "value": "inurl:{target} \"backup\" OR \"backup.zip\""
      },
      {
        "label": "Exposed databases",
        "value": "inurl:{target} filetype:sql OR filetype:db"
      },
      {
        "label": "Local File Inclusion (LFI)",
        "value": "\"{target}\" \"lfi\""
      },
      {
        "label": "Exposed wp-config.php files",
        "value": "\"{target}\" \"wp-config.php\""
      },
      {
        "label": "Visible error messages",
        "value": "inurl:{target} \"error\" OR \"exception\""
      }
    ]
  }
]
```
