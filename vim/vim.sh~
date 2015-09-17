//字段校验处理
:%s/\(\w\+\)/$resume['basic']['\1'] = isset($postData['basic']['\1']) ? $postData['basic']['\1'] : $resume['basic']['\1'];/g


//tel
末尾加空格
:%s/$/;/

:%s/\s//g

:%s/\r//g

:%s/\n//g

