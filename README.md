# bookmarks2fs
create URL shortcuts from Netscape bookmarks file

## Example
### Expected input 
```html
<!DOCTYPE NETSCAPE-Bookmark-file-1>
<!-- This is an automatically generated file.
     It will be read and overwritten.
     DO NOT EDIT! -->
<META HTTP-EQUIV="Content-Type" CONTENT="text/html; charset=UTF-8">
<TITLE>Bookmarks</TITLE>
<H1>Bookmarks</H1>
<DL><p>
    <DT><H3 ADD_DATE="1545502153" LAST_MODIFIED="1546617825" PERSONAL_TOOLBAR_FOLDER="true">Bookmarks bar</H3>
    <DL><p>
        <DT><A HREF="https://habr.com/" ADD_DATE="1545502188">Лучшие публикации за сутки / Хабр</A>
        <DT><A HREF="https://dribbble.com/" ADD_DATE="1546617812" ICON="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAC3klEQVQ4jW2Ty4scVRTGf/fequp6dGW6Z7on8+iZzIwKmoAuFARBXGgWxrVLEQfRlQs3unHhfyAyARGSvyD/QHQjPogIkSwiWY2QmZ7Mq19T3dVV3X2r6rqQbnrEb3XgfOd8fB/nCP6DX57/6Low7IK4CWYTIBf5gcK6r4y488bfd/fn+WJaPGi87+Wl8jfAxzlI13P11VrNMcaQTiam3x0k42zo2ai9Sin+4saTe5PZgodrn/ipp+9LU7y0stHwR+nY73W7bG5dw3XdmdowjjlqHmlh5O9Vt3/zxpN7Ewkw9PWelPLFjRd2lsLwil+r13Ach7OT00v2LMtGKWXn0rwZ6YVvAcRvO7uvZSL7Y7OxnZZDP5iS0zTl8OkByytXqVQqXPR6tFttqotVPM/noNk0Tm6uWwjzqV/yD8uhvzWv5roufhDQPm/RbXdACFbWVgnDEIDA80SR5V9Zxpi3pS3r3U6XPM/JtGYymTAejzHGIISg5JZYbzQQYpY5YVim3em9Y+VCbOmRFv2sj5IS27YphyG1eh3P92i32kRRRDyIKYocKRVKSYSQFJletMjRq5urjh8E8w7Isox2q0V0EVEUBednZ9iOjSkMWZaRZRmgjCWhOUlH1/wgsKbDg8GA0+MTlFLU6jUGgxgpBI3NjZlAp90m6kSxNBY/9+Nhf9rodbscHz2jWq2y/dwO1cVFFhYWSJKEPM/nbmKIcuQjCfJ2nCbVNE3p9/u0zlusra9TW67PQiuHZYwxJEny7/BwyGg0QkrxpXxr/+4jhbhzfPRsdHZySn15mfBKeCkPpRSu65ImCVprTo9P8Dz/x1cff/enBBiI4DNd5I8zY4zrufwfXM8jHsQcPj0ARLO/VHsP5p7ph5c/CMpD57am+NAPAiphWdiOA8agtSa6iBiPx5R896dWot69tb83vrRgil+3d1+xbPm5gVu60EsAjlSRZbsPCpF//fpf3z+c5/8DCLtBoUbfWIUAAAAASUVORK5CYII=">Dribbble - Discover the World’s Top Designers &amp; Creative Professionals</A>
        <DT><H3 ADD_DATE="1545502699" LAST_MODIFIED="1546109756">First level bookmark bar folder</H3>
        <DL><p>
            <DT><H3 ADD_DATE="1545502724" LAST_MODIFIED="1546110214">Second level bookmark bar folder</H3>
            <DL><p>
                <DT><A HREF="https://www.youtube.com/?hl=uk&gl=UA" ADD_DATE="1546109756" ICON="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAABCElEQVQ4ja2TMU4DMRBF38wiEFIqKFYIUSAtJ8kNcoood8jJopwgRyANNCg1aSJl/Sls73rdoBC+NLI982c8/raNAgIHLC2NKZRHg1BHavKvyDlWOGbAG9ACT8RuSgTgCzgA7wbHstpC8Ck4CSSQzDTMp3ZK3EVOvhN8pGAvCILzYGbnYh0SRynn1oEX4JGpME7bOmaO5Lh7daQAPADPDtwnLSKhaaI2q5Wx2RhdZ4RgTIXOBWde7WyYRWLfw3wOux2s12PhaaFQK30xbqqzCSnu1DSw3cJyCfv9GI+Wu3AEneCY1M23ENS2QWZx7h4G/8j7FrxefY25rz8/pH97ytd/puS8+Dv/AFRGv3m23DwSAAAAAElFTkSuQmCC">YouTube</A>
                <DT><H3 ADD_DATE="1546109784" LAST_MODIFIED="1546109784">Third level bookmark bar folder empty</H3>
                <DL><p>
                </DL><p>
                <DT><A HREF="https://translate.google.com/?hl=uk#view=home&op=translate&sl=en&tl=ru&text=Lorem%20ipsum%20dolor%20sit%20amet%2C%20consectetur%20adipiscing%20elit%2C%20sed%20do%20eiusmod%20tempor%20incididunt%20ut%20labore%20et%20dolore%20magna%20aliqua.%20Ut%20enim%20ad%20minim%20veniam%2C%20quis%20nostrud%20exercitation%20ullamco%20laboris%20nisi%20ut%20aliquip%20ex%20ea%20commodo%20consequat.%20Duis%20aute%20irure%20dolor%20in%20reprehenderit%20in%20voluptate%20velit%20esse%20cillum%20dolore%20eu%20fugiat%20nulla%20pariatur.%20Excepteur%20sint%20occaecat%20cupidatat%20non%20proident%2C%20sunt%20in%20culpa%20qui%20officia%20deserunt%20mollit%20anim%20id%20est%20laborum" ADD_DATE="1546109848" ICON="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAACOUlEQVQ4jX2ST0hUURTGf/e+Ny/nn4ma05BOlIYFTZsGoj9Gi2gTRLUoCIpA3bRq1SpoIGpXSyFpWVCrNpFQG1GCiHBRGJkSKISmpM6Yo857954W8ydngrlw4HIv3znf951PXX28+tRop18ELICAACIQNiunX9xJjdPg6EA5/aBBaVRdbZimgUZgAC2UJ9ZNF0BcdS2bnfQaNXClcpP/P5WOuK2HI5+npqanPc+1ruuKtWCMRWuRQiF46VaAu+LQ3+fTHoX5HDx6GyIQmFmN9p4p/u6NRiM4jkZECIUcRIR43LnoVigP9Pm8+eIwMaeJN0FgS++zuQjL+QU8r0A8FkEpVeuBLevtaBYm5jRnD1nunvd5eMkHwIji21KE4laRe8PPERFESrRFhKqExbzi6F7Lu6+a3Aac7LFVY8dnLKsLExzs6uTZyCjLa+t0Jdq5cCrzz8QnYyEG+3xunDAs5RVDo051K2sk2RlvI92T4MfPedLdKY4c2Ie1FrfMhoUc3H8dqtmIlGn6othUnYy8/0C4yeN4uhff93EcBy1SMottJdvAFRnfcy1sFQNQCmMM1lqCIKgNkgC2bJLdBhZgNt/MuWMZ0t0pXo19xBhbkhBsbg1pz7tVnycRUAqU0oiAweVXsZVMqpmWWAQRCzjULrXuZLOfIuOTi+sAsZjD7ZsJkokwSoHWGqUUunGDTGH/Hnc2vEMzeKWN9tZQNQOVHDRsAJDcbR9cv9xMssNBxCJS0m6MYWnlz/BfVT0X3fHmE3AAAAAASUVORK5CYII=">Google Перекладач</A>
            </DL><p>
            <DT><A HREF="https://github.com/" ADD_DATE="1545502680">The world’s leading software development platform · GitHub</A>
        </DL><p>
    </DL><p>
    <DT><A HREF="https://twitter.com/?lang=uk" ADD_DATE="1546110214" ICON="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAACgElEQVQ4jX1TTYscVRQ9577XVdXd00kcDIOT0eC4ELILuBIEV1E3ASHOTpwYcO/KjUL9BQcJBpEkQjYjWQYhboSslWhIVmaSxUwy6gTy0d1VXR/3uKgeMWq88Db33XvuO++eAwBAnhueFRL/lcv1Vz2fKiT1j1IC0NJXD1/uJfEk4Ikau7pzZuFnbCpZevDbIT7/dflqFmZvba8f3AAAbCpgjS1yGXL6C+cfvR3T7BJ7ySII+GRcwuI3aKthK56LWZi9xmz0+crF8fL2neGnWGOzP35x48GBYPiSFhZ98mQGkoAyG2QfaepbbHXFBO2qLmDZ8JOVV6bXVi5O30V+b4CcHkZxCeBRL6cuIgHUA9moamq5/0T6VWJD6ZHR428t678DVwQJVcUWyB8gOIDTJIIASRBID/1hqKeP37u/fuhyXF549IZZTFHNXEQDd2MvXWWSrkKAiieA1L2eIOBBs5KBnAJAdKa/Guo3mS0kKsZOkmoqV1P5/CsCSarbiNMi1TaTMsTrAGC7p/t3nTiFtr5NowPQfH2B3YG6nAQ50j4AXNt7f3gfEA0A7m2NvkNV3iRtHwDkvKtDI0ARBNqWgr7oBAVap7Rb5mY7NhgkjGmA1NHucChAkBobjqKXk8s76wevQCJy+lMyXb4wPhFC+EzA6/JaBAyAQ3IbHuh5Obne1Dqx++HC3lzEii9devhcUVWpKT0K+nG4r9Bi0+laxpgG9pLQFpPvZ3Wxvnfm8B+AuE81NrUdS5l9zBBO2uKghxZQA6gWUBUub294MT6788Ho3Nw0c1Z/N1Mue3G1OuYoj1M8IrgR9jsQf9nu93/EGtv/ap5b83+svB+bCs+6+hMimjBxQ9TbGwAAAABJRU5ErkJggg==">Твіттер. Все, що актуально.</A>
    <DT><A HREF="https://www.reddit.com/" ADD_DATE="1546617410" ICON="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAACdUlEQVQ4jWXTTYjVdRTG8c/5/e+945hNMhLEgFRUA1lgNYHojJjpDXduQkSqjRiKJNSu2rRJV0VQi14IKohCW8UEIRJZ05uUGESrBBOsJocayRznvvxPizup0dmcxeF5zoHzfAOSCBKybRP2SpO4SUjMSjOKV+Ooz67VhKXKdUZc75CwWzGk/neAQBXUuSi9oevp+NRFiCRMGDHqiIa2rkSNgqu3Xc5aUQwLfR9bsCO+8FcjyLzBIQ1tPR2hIVWD7ZEeforMsPLGyh331g7u6rr4xzbDnseBkltNqezW0xfRIIqqpDrSytHQGg7Tb6XZM6mzWNDQUwuP5xbrI9veU+xU61tUBHpCB+vWs3qcd9+mhYbUxDK1UKm905AmpdQTbh2n2wnj97F5F7fcRd1j7WaOv89Pp0JzKP36c2hKTMmHymJulHlgQ51/X8i8MJdZ9/N/1e9lzp3LnD+fuW+izo0y26VTXPljDvrIKl5+gn330+/R67B3gjefYdUYzSFKdUVWZD1reaRvv0rffJT6fe6epP0YVYNGi8nt3LxmYHjyWDp1Ii2Xsj5bpM+VCEX6+kNZVTy4i3s2Mf878+fZsJ32o7JqcGJ6EK8SIcxUz91mVp2PaEZx+gcREcYn0ty5cPp7fjvD8HVpZFQceSEcfjG1hDo7evYH5BavGLJfR8dlDXeuLR7YkcZuH8T4l9Ph+Af8eLLW0tfS1PVSHPPkIMqTVhh2WNM2/UgLWesITQNWulJLGo6iytA1rdjpqEtXYVpjhTEHhT2qsoygXiKqlAFVvXoBr/nTs/GdS5Y4+y/OW01hD6awesn/rDCj7/X4xJfXav4BhnocQyGrEocAAAAASUVORK5CYII=">reddit: the front page of the internet</A>
    <DT><H3 ADD_DATE="1546628225" LAST_MODIFIED="1546628335">folder on other</H3>
    <DL><p>
        <DT><A HREF="https://www.theverge.com/" ADD_DATE="1546628325" ICON="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAACW0lEQVQ4jaWSTUgUcQDF3392doapcWfXndlZESqV/IjMCqGgQ3krDCsQulSC1R68aGJBhyL3UJcoD2IQBdGHdCkKMvBkBh1KisXA2Qrs04/G1WVZZ/W/6/8/XVIW7Ut6x8f7vcPjAf8p0v803nj50kDPvwISB7reL8C3XoXcf6hFjMU+n6+uCRp/A8e+OfjyKY3Dkwz+KYbkxWpg2r4gNjXX3E8kEtV/ghnj6Dz7CsGsi0abgdaFkN0ZhO7z9YqmaV5JpVInFmynpPDkEMTa8KDv5t6W/ILeO68jE+OZ1vYJBtlDkDhdAdHr/WiaZpdACJkPhUIdbkAC3aWD3P2wW3g2psuyPCLL8gil1L53a/hYhcOxJ8nhHN0Atm4twuHwGUJIRgAAv9//SFGUASdSBqbLmO143uW6rggA3VeHopk0DUTGGHhQghMpg6IoA5qmPQQAAQAIIdw0zTaoXjbbthHsbWIbvRZrjse/b+l7PBKpS3KUZ1zMtpYDBV5mmmY7IYQvFQCAqqrDmqZdn2soRm6zD865F9GezsFuKcc9TeMMuU0+zB0shqZpN1RVjS39IH8s13VDlmXFPW+mA4VHXuJBSIALoNHmmLm9A6w2mKyqqqokhNiLjJBfQAixDcOI5rYGMF9fhIYpjgNTHPP7ipDbHoBhGNF8eEUBAOi63iNJkpU+VQFR9sArC0i3l0OSpHe6rq94rLjcIIRkU6lUx9dsts85XgK4AC9S8HO47Ir8cmNRo6OjTzIz6Xq4wJpgQV9paen+32V/KUpppWVZk5ZlTVJKK1cFr0Y/ANRF5HVK9bTiAAAAAElFTkSuQmCC">The Verge</A>
    </DL><p>
</DL><p>

```
### As result, you get following folder structure
```
$ tree
.
├── Bookmarks bar
│   ├── Dribbble - Discover the World’s Top Designers & Creative Professionals.desktop
│   ├── First level bookmark bar folder
│   │   ├── Second level bookmark bar folder
│   │   │   ├── Google Перекладач.desktop
│   │   │   └── YouTube.desktop
│   │   └── The world’s leading software development platform · GitHub.desktop
│   └── Лучшие публикации за сутки  Хабр.desktop
├── icons
│   ├── dribbble.png
│   ├── reddit.png
│   ├── theverge.png
│   ├── translate.png
│   ├── twitter.png
│   └── youtube.png
└── Other bookmarks
    ├── folder on other
    │   └── The Verge.desktop
    ├── reddit: the front page of the internet.desktop
    └── Твіттер. Все, що актуально..desktop
```