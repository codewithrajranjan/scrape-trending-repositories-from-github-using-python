### Scrape GitHub Trending repositories using Python

- we will be scraping the trending repositories from GitHub webiste
- Following libraries are used
 - requests
 - BeautifulSoup4
 

### Installation

```bash
    pip install -r requirements.txt
```

### Run the program

```bash
    python app.py
```

### Sample Output

```python
    [{'label': 'nhsx/COVID-19-app-iOS-BETA',
      'link': 'https://github.com/nhsx/COVID-19-app-iOS-BETA'},
     {'label': 'nhsx/COVID-19-app-Android-BETA',
      'link': 'https://github.com/nhsx/COVID-19-app-Android-BETA'},
     {'label': 'MITDDC/zork', 'link': 'https://github.com/MITDDC/zork'},
     {'label': 'denoland/deno', 'link': 'https://github.com/denoland/deno'},
     {'label': 'GoogleChrome/web-vitals-extension',
      'link': 'https://github.com/GoogleChrome/web-vitals-extension'},
     {'label': 'beekeeper-studio/beekeeper-studio',
      'link': 'https://github.com/beekeeper-studio/beekeeper-studio'},
     {'label': 'mrc-ide/covid-sim', 'link': 'https://github.com/mrc-ide/covid-sim'},
     {'label': 'xuxueli/xxl-job', 'link': 'https://github.com/xuxueli/xxl-job'},
     {'label': 'vueComponent/ant-design-vue-pro',
      'link': 'https://github.com/vueComponent/ant-design-vue-pro'},
     {'label': 'keybase/client', 'link': 'https://github.com/keybase/client'},
     {'label': 'alibaba/easyexcel', 'link': 'https://github.com/alibaba/easyexcel'},
     {'label': 'nhsx/COVID-19-app-Documentation-BETA',
      'link': 'https://github.com/nhsx/COVID-19-app-Documentation-BETA'},
     {'label': 'microsoft/playwright',
      'link': 'https://github.com/microsoft/playwright'},
     {'label': 'evanw/esbuild', 'link': 'https://github.com/evanw/esbuild'},
     {'label': 'manchenkoff/skillbox-async-messenger',
      'link': 'https://github.com/manchenkoff/skillbox-async-messenger'},
     {'label': 'id-Software/DOOM', 'link': 'https://github.com/id-Software/DOOM'},
     {'label': 'MustangYM/WeChatExtension-ForMac',
      'link': 'https://github.com/MustangYM/WeChatExtension-ForMac'},
     {'label': 'donnemartin/system-design-primer',
      'link': 'https://github.com/donnemartin/system-design-primer'},
     {'label': 'bradtraversy/design-resources-for-developers',
      'link': 'https://github.com/bradtraversy/design-resources-for-developers'},
     {'label': '0voice/interview_internal_reference',
      'link': 'https://github.com/0voice/interview_internal_reference'},
     {'label': 'AobingJava/JavaFamily',
      'link': 'https://github.com/AobingJava/JavaFamily'},
     {'label': 'luruke/browser-2020',
      'link': 'https://github.com/luruke/browser-2020'},
     {'label': 'tonlabs/main.ton.dev',
      'link': 'https://github.com/tonlabs/main.ton.dev'},
     {'label': 'Snailclimb/JavaGuide',
      'link': 'https://github.com/Snailclimb/JavaGuide'},
     {'label': 'labuladong/fucking-algorithm',
      'link': 'https://github.com/labuladong/fucking-algorithm'}]

```