Thug
==================================================

This is not a Model in the traditional sense
this provides functions to control an account
object. The Account object has state but this
is only to describe rolodex what kind of behavior
it should apply to the object that is passed in.

    var account = new Thug({
      locals: {},
      filters: {
        in     : [],
        before : [],
        after  : [],
        out    : []
      },
      validations: {}
    })

    account.validate(obj, function(errors, obj){
      ...
    })

    account.validate(id, obj, function(errors, obj){
      ...
    })

    account.create(obj, function(errors, obj){
      ...
    })

    account.update(id, obj, function(errors, obj){
      ...
    })

    account.get(id, function(obj){
      ...
    })

    account.get({ property: value }, function(obj){
      ...
    })

    account.destroy(id, function(errors, obj){
      ...
    })

Copyright 2012 Chloi Inc.
All rights reserved.

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
