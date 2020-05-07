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
