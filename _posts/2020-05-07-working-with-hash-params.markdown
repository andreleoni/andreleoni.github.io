---
layout: post
title:  "Working with hash params"
date:   2020-05-07 19:30:41 -0300
categories: jekyll update
---
```
test_hash = { a: 1 }

def merge_on_hash(hash)
  hash.merge!(b: 2)
end

merge_on_hash(test_hash)

puts test_hash
```

Result:

```
irb(main):017:0> puts test_hash
{:a=>1, :b=>2}
```
