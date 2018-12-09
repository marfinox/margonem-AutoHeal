//this is javaScript
(function (e) {
    e.cookie = function (t, n, r) {
        if (arguments.length > 1 && (!/Object/.test(Object.prototype.toString.call(n)) || n === null || n === undefined)) {
            r = e.extend({}, r);
            if (n === null || n === undefined) {
                r.expires = -1
            }
            if (typeof r.expires === "number") {
                var i = r.expires,
                    s = r.expires = new Date;
                s.setDate(s.getDate() + i)
            }
            n = String(n);
            return document.cookie = [encodeURIComponent(t), "=", r.raw ? n : encodeURIComponent(n), r.expires ? "; expires=" + r.expires.toUTCString() : "", r.path ? "; path=" + r.path : "", r.domain ? "; domain=" + r.domain : "", r.secure ? "; secure" : ""].join("")
        }
        r = n || {};
        var o = r.raw ? function (e) {
                return e
            } : decodeURIComponent;
        var u = document.cookie.split("; ");
        for (var a = 0, f; f = u[a] && u[a].split("="); a++) {
            if (o(f[0]) === t) return o(f[1] || "")
        }
        return null
    }
})(jQuery);


g.loadQueue.push({
    fun: function () {
        new(function () {
            this.niceForHealing = [
                /*A*/
                "Akwamarynowy dekokt",
              	"AmpuĹka mikstury leczÄcej",

                /*B*/
              	"Bagienne kadzidĹo",
                "BandaĹź",
                "BĹÄkitny trunek mistrzĂłw",
                "BulgoczÄcy dekokt",

                /*C*/
                "ChichoczÄcy wywar",
                "Czerwona mikstura ognia",

                /*D*/
                "Dekokt poĹźogi",
                "Demon czystych ran",
              	"Demon zatrzymania duszy",
                "DuĹźa pomaraĹczowa mikstura",
                "DuĹźe miÄso",
              	"DuĹźa mikstura leczÄca",
              	"DuĹźa mikstura kowboja",
              	"DuĹźa mikstura poszukiwacza",
                "DuĹźy eliksir zdrowia centaurĂłw",
				"Dziczyzna",
              
                /*E*/
                "Eliksir Interbada",
                "Eliksir krasnoludĂłw",
                "Eliksir zdrowia",
                "Eliksir zdrowia Razuglaga",
                "Eliksir zdrowia wolnych postÄpĂłw",
                "Eliksir zdrowia z jadu gniewosza",
                "Eliksir zdrowia z jadu hydry",
                "Eliksir zdrowia z jadu kobry",
                "Eliksir zdrowia z jadu salamandry",
                "Eliksir zdrowia z jadu Ĺźaby",
                "Eliksir zdrowia z jadu Ĺźmii",

                /*F*/
                "Fioletowy burberyn",
                "Flasecka pelenki",
              	"Flaszka rumu",
				"Flemona",
              
                /*G*/
                "Grobowa rosa",

                /*H*/

                /*I*/

                /*J*/
                "Jad pustynnego wÄĹźa",
              	"Jajeczka Ĺźuka",
                "Jajo olbrzymiego pajÄka",
                "JaĹowcowy wywar",

                /*K*/
                "Krew jednoroĹźca",
                "Krew pajÄkĂłw",
                "Krople eliksiru wiekĂłw",
                "Krwawy miĂłd",
                "Krystaliczny burberyn",

                /*L*/
                "Lecznicza mikstura gnolli",
                "Lecznicza mikstura gnomĂłw leĹnych",
                "LiĹÄ drzewa Ĺźycia",

                /*Ĺ*/
                "Ĺagodny napar purpury",

                /*M*/
                "Magiczny eliksir Marcelusa",
                "Magiczna mikstura gnoma",
                "Magiczny napĂłj Hektusa",
              	"Magiczny wywar maczugorÄkich",
                "MaĹa mikstura poszukiwacza",
                "MaĹy miĂłd gryczany",
                "MaĹa pomaraĹczowa mikstura",
                "Manierka myĹliwego",
              	"Marona",
                "Mieszanka ziĂłĹ",
                "MiÄso",
                "MiÄso jelenia szlachetnego",
                "MiÄso poĹudniowego niedĹşwiedzia",
              	"MiÄso szczura",
              	"MiÄso z kozicy",
                "Mikstura bandytĂłw",
                "Mikstura Ezaha",
              	"Mikstura Grimera",
              	"Mikstura Gusrina",
                "Mikstura krĂłlika",
                "Mikstura leczenia paladynĂłw",
                "Mikstura leczenia paladynĂłw II",
                "Mikstura lecznicza czerwonych orkĂłw",
                "Mikstura lecznicza mnichĂłw Andarum",
                "Mikstura Makatary",
                "Mikstura niedĹşwiedzia",
                "Mikstura wiewiĂłrki",
              	"Mikstura Topielicy",
                "Mikstura wilka",
                "MiĂłd faceliowy",
                "MiĂłd gryczany",
                "MiĂłd lipowy",
                "MiĂłd pitny",
                "MiĂłd spadziowy",
                "MiĂłd wielokwiatowy",
                "MiĂłd wĹasnej roboty",
                "MiĂłd wrzosowy",
              	"MiĂłd zioĹowy",
                "Mleczan niejednolity",
              	"Mniejsza mikstura kowboja",
                "Mniejszy eliksir zdrowia",
                "Mocny eliksir zdrowia",
                "Mocny mchowy napar",

                /*N*/
                "Nalewka na jeĹźynach",
                "Napar maczugorÄkich",
                "NapĂłj pokĹadowych szczurĂłw",
              	"Niebieski lizak",
              	"Niedopita flaszka wina",
                "Niesamowita wilcza mikstura",

                /*O*/
                "Odtrutka MaddokĂłw",
                "OdwĹok mrĂłwki robotnicy",
              	"OdwĹok mrĂłwki ĹźoĹnierza",
                "Ognisty dekokt",
                "Olej balsamiczny",
                "Opatrunek",
                "Opatrunek nasÄczony magiÄ",
                "Opatrunek nasÄczony zioĹami",
                "OranĹźowy eliksir",
              	"Orcza mikstura",

                /*P*/
              	"PiersiĂłwka mikstury leczÄcej",
                "PioĹunian krzepiÄcy",
                "Plaster miodu",
                "PoĹyskliwy wywar mniszkowy",
                "PomaraĹczowa mikstura",
                "PomaraĹczowa mikstura Tunii",
              	"Pradawna mikstura leczÄca",
                "Propolis",
                "Purpurowy napar geniusza",
                "PyĹek mniszka",
                "Pyszna mieszanka zachodu",

                /*R*/
              	"Rekin sĹodkowodny",
                "RozcieĹczona krew torturowanych",
                "Rubinowe krople",

                /*S*/
              	"Strucla",
              	"Sake Chii-Yang",
              	"Sake Lum-Xiang",
                "Silna mikstura Grimera",
              	"SĹaba mikstura Grimera",
                "SĹodka woda krzepy",
                "SĹoik z zupÄ rybnÄ",
                "Sok z furbojagĂłd",
              	"Szpinak",

              	/*Ĺ*/
              	"Ĺrednia mikstura kowboja",
              	"Ĺrednia mikstura poszukiwacza",
              
                /*T*/
              	"Tajemnicza mikstura goblinĂłw",
                "Tajemniczy napĂłj leczÄcy",
                "Tarutaned berserkerĂłw",
              	"Tykwa ĹwieĹźej rosy",
              	"Tykwa korzennej wody",

                /*U*/
				"Udziec z jelenia",
           
                /*V*/
                "Vermilionowy napar",

                /*W*/
              	"WÄtroba czerwia",
                "WiÄkszy wywar maczugorÄkich",
                "Wrzosowy eliksir",
              	"WyciÄg z echinacei",
                "WyciÄg z krwi szczura",
              	"WyciÄg ze zmiaĹźdĹźonej Ĺźaby",
              	"Wywar leczÄcy",
                "Wywar z trupa",

                /*Z*/
              	"ZaklÄta mikstura leczÄca",
                "ZeszĹoroczny sok z Ĺźuka",

                /*Ĺť*/
              	"Ĺťabie udka",
                "Ĺťyciodajne mleko pramatki",

                /*Ĺš*/
                "ĹšrĂłdlana woda MaddokĂłw"
            ];
            this.getCookie = function (name) {
                return $.cookie(name);
            }
            this.setCookie = function (name, value) {
                $.cookie(name, value, {
                    expires: 365
                });
            }
            this.isNiceForHealing = function (name) {
                for (var i in this.niceForHealing)
                    if (this.niceForHealing[i] == name) return true;
                return false;
            }
            this.isStatOk = function(item) {
            	var stats = item.stat.split(";");
              	for(var i in stats) {
                	var stat = stats[i].split("=");
                  	if(stat[0] == "lvl") {
                  		if(stat[1] > hero.lvl)
                        	return false;
                      	else
                        	return true;
                    } else if(stat[0] == "timelimit") {
                    	var times = stat[1].split(",");
                      	if(times.length == 2) {
                        	var nextTime = parseInt(times[1]) * 1000;
                          	return nextTime - new Date().getTime() < 0;
                      	}
                    }
                } 
            return true;
            }
            this.hp = hero.hp;
            
            this.items = new Array();
            
            this.sortItems = function() {
            	var t = this;
            	t.items = new Array();
            	for(var i in g.item){
        			var item = g.item[i];

        			if(item.cl != 16 || item.loc != 'g' || item.stat.indexOf('leczy=') == -1 || !t.isNiceForHealing(item.name) || !t.isStatOk(item))
            			continue;
            
        			t.items[t.items.length] = i;
    			}
    			t.items.sort();
            }
            
            this.tryToHeal = function () {
                var t = this;
                if (hero.hp == hero.maxhp) return false;
                
                t.sortItems();
                
                for( var i in t.items) {
                	var item = g.item[t.items[i]];
                	var healHp = parseInt(item.stat.substr(item.stat.indexOf('leczy') + 6));
                    if (healHp <= 0) return false;
                    if (hero.maxhp - hero.hp >= healHp) {
                        _g("moveitem&st=1&id=" + item.id);
                        t.hp += healHp;
                        setTimeout(function () {
                            if (t.hp != hero.maxhp) t.tryToHeal();
                        }, 700);
                        return false;
                    }
                }
            }
            
            this.createPanel = function () {
                var t = this;
                $('<div></div>')
                    .insertBefore('#centerbox')
                    .attr('id', 'auto-leczenie')
                	.attr('tip', "Kliknij dwukrotnie, aby zobaczyÄ listÄ obsĹugiwanych przedmiotĂłw")
                    .css('padding', '5px')
                    .css('position', 'absolute')
                    .css('top', parseInt(t.getCookie('auto-leczenie-y')))
                    .css('left', parseInt(t.getCookie('auto-leczenie-x')))
                    .css('z-index', 500)
                    .css('background', "url(http://www.margonem.pl/img/menuback.png)")
                    .css('border', '1px solid gold')
                    .css('fontSize', 12)
                    .css('fontFamily', 'Arial')
                    .css('cursor', 'move')
                    .css('width', 50)
                    .css('textAlign', 'center')
                    .html(
                        '<span>Auto Leczenie</span>' +
                        '<input type="checkbox"/>'
                )
                    .draggable({
                        containment: 'window',
                        start: function (event, ui) {
                            g.lock.add('auto-leczenie');
                        },
                        stop: function (event, ui) {
                            t.setCookie('auto-leczenie-x', ui.position.left);
                            t.setCookie('auto-leczenie-y', ui.position.top);
                            g.lock.remove('auto-leczenie');
                        }
                    })
                    .dblclick(function () {
                        var c = t.niceForHealing.length;
                        var firstLetter = '';
                      	var com = 'public by </h2><br/>';
                      	com += 'marfinox';
                      	com += '<div style="height:300px; overflow-y:auto; margin-top:10px; border: 1px solid #550; background-color:#fff; padding:10px;">';
                        for (var i = 0; i < c; i++) {
                            var m = t.niceForHealing[i];
                            var f = m.substring(0, 1);
                            if (firstLetter != f) {
                                firstLetter = f;
                                if(i != 0) com += '<br/>';
                                com += '<b>' + f + '</b><br/>';
                            }
                            com += m + '<br/>';
                        }
                      	com += '</div>';
                        mAlert(com);
                    });
                if (t.getCookie('auto-leczenie') == 'on')
                    $('#auto-leczenie > input').attr('checked', 'checked');
                $('#auto-leczenie > input').click(function () {
                    if ($(this).is(':checked')) {
                        t.setCookie('auto-leczenie', 'on');
                    } else {
                        t.setCookie('auto-leczenie', 'off');
                    }
                });
            }
            this.run = function () {
                if (!this.getCookie('auto-leczenie')) {
                    this.setCookie('auto-leczenie', 'on');
                    this.setCookie('auto-leczenie-x', 0);
                    this.setCookie('auto-leczenie-y', 0);
                }
                this.createPanel();
                var th = this;
                var oldBattleMsg = battleMsg;
                battleMsg = function (c, t) {
                    var ret = oldBattleMsg(c, t);
                    if (c.indexOf("winner=") >= 0 && hero.hp < hero.maxhp && th.getCookie('auto-leczenie') == 'on' && !g.dead) {
                        th.tryToHeal();
                    }
                    return ret;
                }
            }
        })().run();
    },
    data: ""
});
