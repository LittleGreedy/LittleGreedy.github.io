---
title: about
date: 2018-12-12 22:14:36
keywords: 关于
description: 
comments: false
photos: https://cdn.jsdelivr.net/gh/honjun/cdn@1.4/img/banner/about.jpg
---
{% raw %}
<div class="moe-littleGreedy" style="text-align:center; font-size: 50px; margin-bottom: 20px;">[さくら荘のlittleGreedy]</div>
<div id="hello-littlezero" class="popcontainer" style="min-height: 300px; padding: 2px 6px 4px; background-color: rgba(242, 242, 242, 0.5); border-radius: 10px;">
  <center>
  <p>
  </p>
  <h4>
  与&nbsp;<ruby>
  Zero&nbsp;<rp>
  （</rp>
  <rt>
  小 零 号（ゼロ）</rt>
  <rp>
  ）</rp>
  </ruby>
  对话中...</h4>
  <p>
  </p>
  </center>
  <bot-ui></botui>
</div>
<script src="https://cdn.jsdelivr.net/vue/latest/vue.min.js"></script>
<script src="https://unpkg.com/botui/build/botui.min.js"></script>
<script>
function bot_ui_ini() {
    var botui = new BotUI("hello-mashiro");
    botui.message.add({
        delay: 800,
        content: "Hi, there111👋"
    }).then(function () {
        botui.message.add({
            delay: 1100,
            content: "这里是 Mashiro"
        }).then(function () {
            botui.message.add({
                delay: 1100,
                content: "一个可爱的蓝孩子~"
            }).then(function () {
                botui.action.button({
                    delay: 1600,
                    action: [{
                        text: "然后呢？ 😃",
                        value: "sure"
                    }, {
                        text: "少废话！ 🙄",
                        value: "skip"
                    }]
                }).then(function (a) {
                    "sure" == a.value && sure();
                    "skip" == a.value && end()
                })
            })
        })
    });
    var sure = function () {
            botui.message.add({
                delay: 600,
                content: "😘"
            }).then(function () {
                secondpart()
            })
        },
        end = function () {
            botui.message.add({
                delay: 600,
                content: "![...](https://view.moezx.cc/images/2018/05/06/a1c4cd0452528b572af37952489372b6.md.jpg)"
            })
        },
        secondpart = function () {
            botui.message.add({
                delay: 1500,
                content: "目前就读于上海财经大学"
            }).then(function () {
                botui.message.add({
                    delay: 1500,
                    content: "向往技术却误入商科，但后来喜欢上了经济学…"
                }).then(function () {
                    botui.message.add({
                        delay: 1200,
                        content: "因为数据分析也需要Coder嘛"
                    }).then(function () {
                        botui.message.add({
                            delay: 1500,
                            content: "主攻 R 语言和 Python，略懂 STATA，偶尔也折腾 HTML/CSS/JavaScript/PHP"
                        }).then(function () {
                            botui.message.add({
                                delay: 1500,
                                content: "研究的方向，是经济/金融方向的数据分析（data science）以及机器学习（machine learning）"
                            }).then(function () {
                                botui.message.add({
                                    delay: 1800,
                                    content: "喜欢画画，希望有一天能够被称为画师"
                                }).then(function () {
                                    botui.action.button({
                                        delay: 1100,
                                        action: [{
                                            text: "为什么叫Mashiro呢？ 🤔",
                                            value: "why-mashiro"
                                        }]
                                    }).then(function (a) {
                                        thirdpart()
                                    })
                                })
                            })
                        })
                    })
                })
            })
        },
        thirdpart = function () {
            botui.message.add({
                delay: 1E3,
                content: "Mashiro以及站名都来自一部动画，因为和主角有一样的爱好~ 如果有兴趣可以找找首页上的视频~"
            }).then(function () {
                botui.action.button({
                    delay: 1500,
                    action: [{
                        text: "为什么是白猫呢？ 🤔",
                        value: "why-cat"
                    }]
                }).then(function (a) {
                    fourthpart()
                })
            })
        },
        fourthpart = function () {
            botui.message.add({
                delay: 1E3,
                content: "因为对GitHub有种执念… "
            }).then(function () {
                botui.message.add({
                    delay: 1100,
                    content: "而且我真的是猫控！"
                }).then(function () {
                    botui.action.button({
                        delay: 1500,
                        action: [{
                            text: "域名有什么含意吗？(ง •_•)ง",
                            value: "why-domain"
                        }]
                    }).then(function (a) {
                        fifthpart()
                    })
                })
            })
        },
        fifthpart = function () {
            botui.message.add({
                delay: 1E3,
                content: "emmmm，看备案信息你就知道了=.= 本来想要zheng.xin的，但50万真买不起。。"
            }).then(function () {
                botui.message.add({
                    delay: 1600,
                    content: "那么，仔细看看我的博客吧？ ^_^"
                })
            })
        } 
}
bot_ui_ini()
</script>

<script>
function bot_ui_ini() {
    var botui = new BotUI("hello-littlezero");
    botui.message.add({
        delay: 800,
        content: "Hi, there111👋"
    }).then(function () {
        botui.message.add({
            delay: 1100,
            content: "这里是 Zero"
        }).then(function () {
            botui.message.add({
                delay: 1100,
                content: "一个可爱的蓝孩子~"
            }).then(function () {
                botui.action.button({
                    delay: 1600,
                    action: [{
                        text: "然后呢？ 😃",
                        value: "sure"
                    }, {
                        text: "少废话！ 🙄",
                        value: "skip"
                    }]
                }).then(function (a) {
                    "sure" == a.value && sure();
                    "skip" == a.value && end()
                })
            })
        })
    });
    var sure = function () {
            botui.message.add({
                delay: 600,
                content: "😘"
            }).then(function () {
                secondpart()
            })
        },
        end = function () {
            botui.message.add({
                delay: 600,
                content: "![...](https://view.moezx.cc/images/2018/05/06/a1c4cd0452528b572af37952489372b6.md.jpg)"
            })
        },
        secondpart = function () {
            botui.message.add({
                delay: 1500,
                content: "一个ACMer~ 比Oier蒻一大截的那种"
            }).then(function () {
                botui.message.add({
                    delay: 1500,
                    content: "向往技术，偶尔折腾些新花样…"
                }).then(function () {
                    botui.message.add({
                        delay: 1200,
                        content: "总喜欢站在Coder的角度写点小程序"
                    }).then(function () {
                        botui.message.add({
                            delay: 1500,
                            content: "主攻 C++ 语言和 算法，略懂 Python 语言，偶尔捣鼓 HTML/CSS/JavaScript/PHP"
                        }).then(function () {
                            botui.message.add({
                                delay: 1500,
                                content: "折腾的方向，是 Web前端（front-end ）以及人工智能（artificial intelligence）"
							}).then(function () {
								botui.message.add({
									delay: 600,
									content: "![...](https://raw.githubusercontent.com/littlegreedy/zero/master/images/wallpaper/web.png)"
									}).then(function () {
										botui.message.add({
											delay: 1800,
											content: "喜欢画画，希望有一天能够被称为画师"
										}).then(function () {
											botui.action.button({
												delay: 1100,
												action: [{
													text: "为什么叫littlezero呢？ 🤔",
													value: "why-littlezero"
											}]
										}).then(function (a) {
											thirdpart()
										})
									})	
                                })
                            })
                        })
                    })
                })
            })
        },
        thirdpart = function () {
            botui.message.add({
                delay: 1E3,
                content: "零号来自一本书里的角色，因为每次对其出场都欢喜不已，便取littlezero小零号为名~ 如果有兴趣可以找找首页上的视频~"
            }).then(function () {
                botui.action.button({
                    delay: 1500,
                    action: [{
                        text: "为什么昵称是小贪心呢？ 🤔",
                        value: "why-cat"
                    }]
                }).then(function (a) {
                    fourthpart()
                })
            })
        },
        fourthpart = function () {
            botui.message.add({
                delay: 1E3,
                content: "因为对贪心算法有种执念… "
            }).then(function () {
                botui.message.add({
                    delay: 1300,
                    content: "大一下学期开学的时候刷《啊哈！算法》，最后学到树便停下来了，而停下来的下一章就是贪心：“局部代整体，贪婪地选取最优解"
                }).then(function () {
                    botui.action.button({
                        delay: 1500,
                        action: [{
                            text: "域名有什么含意吗？(ง •_•)ง",
                            value: "why-domain"
                        }]
                    }).then(function (a) {
                        fifthpart()
                    })
                })
            })
        },
        fifthpart = function () {
            botui.message.add({
                delay: 1E3,
                content: "emmmm，看备案信息你就知道了=.= 本来想要zero的，但真滴买不到。。。"
            }).then(function () {
                botui.message.add({
                    delay: 1600,
                    content: "那么，请仔细看看我的博客吧？ ^_^"
                })
            })
        } 
}
bot_ui_ini()
</script>
{% endraw %}