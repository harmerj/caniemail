---
title: "<textarea> element"
description: "HTML input type text"
category: html
keywords: form, text
last_test_date: "2019-09-10"
test_url: "tests/html-forms.html"
test_results_url: "https://app.emailonacid.com/app/acidtest/MOk8g8TWwCTL4vLGrdMIgu3Vncqdxif6KlK4g8HfUV1mB/list"
stats: {
    apple-mail: {
        macos: {
            "10.3":"y #1",
            "12.4":"y #1"
        },
        ios: {
            "10.3":"y #2",
            "12.4":"y #2"
        }
    },
    gmail: {
        desktop-webmail: {
            "2019-09":"y"
        },
        ios: {
            "2019-09":"y"
        },
        android: {
            "2019-09":"y"
        }
    },
    outlook: {
        windows: {
            "2003":"n",
            "2007":"n",
            "2010":"n",
            "2013":"n",
            "2016":"n",
            "2019":"n"
        },
        macos: {
            "2011":"y",
            "2016":"y",
            "2019":"y"
        },
        outlook-com: {
            "2019-09":"y"
        },
        ios: {
            "2019-06":"y"
        },
        android: {
            "2019-06":"n #3"
        }
    },
    samsung-email: {
        android: {
            "6.0":"n #3",
            "9.0":"n #3"
        }
    },
    yahoo: {
        desktop-webmail: {
            "2019-09":"y"
        },
        ios: {
            "2019-09":"y"
        },
        android: {
            "2019-09":"n #3"
        }
    },
    aol: {
        desktop-webmail: {
            "2019-09": "y"
        },
        ios: {
            "2019-09": "y"
        },
        android: {
            "2019-09": "y"
        }
    }
}
notes: ""
notes_by_num: {
  "1": "Buggy. Email scrolls to the end when space bar is pressed.  This can be fixed by wrapping the `<input>` in `<ul role=\"presentation\">`.",
  "2": "Buggy. Screen jumps when input is in focus.",
  "3": "Buggy. A number of android clients will not show the keyboard when the input is clicked.  Copy and pasting text works."
}
---