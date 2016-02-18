be sure to enter the text below into irssi if u want left-aligned nicks
doesn't work w/ nickcolor.pl

'''
/format own_msg {ownmsgnick $2 {ownnick $[-9]0}}$1
/format own_msg_channel {ownmsgnick $3 {ownnick $[-9]0}{msgchannel $1}}$2
/format pubmsg_me {pubmsgmenick $2 {menick $[-9]0}}$1
/format pubmsg_me_channel {pubmsgmenick $3 {menick $[-9]0}{msgchannel $1}}$2
/format pubmsg_hilight {pubmsghinick $0 $3 $[-9]1}$2
/format pubmsg_hilight_channel {pubmsghinick $0 $4 $[-9]1{msgchannel $2}}$3
/format pubmsg {pubmsgnick $2 {pubnick $[-9]0}}$1
/format pubmsg_channel {pubmsgnick $3 {pubnick $[-9]0}{msgchannel $1}}$2

'''
