# Dictionary.com-Bookmarklet
This is a bookmarklet for quickly searching a word in Dictionary.com. <p>To install it, just drag the <a class="bookmarklet" href="javascript:void (function(){try{var b=window.getSelection(),a=b?b.toString().replace(/(^\W+|\W+$)/g,''):'';if(!a){a=prompt('Enter a word to look up');if(!a)return}var c='https://www.dictionary.com/browse/'+encodeURIComponent(a)+'?s=t';window.open(c)}catch(d){alert('Oops:\n'+d.message)}})();">Define</a> Bookmarklet into your browser bookmarks bar</p>
  the compressed code is:
  javascript:void (function(){try{var b=window.getSelection(),a=b?b.toString().replace(/(^\W+|\W+$)/g,''):'';if(!a){a=prompt('Enter a word to look up');if(!a)return}var c='https://www.dictionary.com/browse/'+encodeURIComponent(a)+'?s=t';window.open(c)}catch(d){alert('Oops:\n'+d.message)}})();

The uncompress code is: <br>
javascript: void(function() { <br>
    try { <br>
        var b = window.getSelection(), <br>
            a = b ? b.toString().replace(/(^\W+|\W+$)/g, '') : ''; <br>
        if (!a) { <br>
            a = prompt('Enter a word to look up'); <br>
            if (!a) return <br>
        } <br>
        var c = 'https://www.dictionary.com/browse/' + encodeURIComponent(a) + '?s=t'; <br>
        window.open(c) <br>
    } catch (d) { <br>
        alert('Oops:\n' + d.message) <br>
    } <br>
})(); <br>
