{% highlight clojure linenos %}
(defn pr-str
  "pr to a string, returning it"
  {:tag String
   :added "1.0"
   :static true}
  [& xs]
    (with-out-str
     (apply pr xs)))
{% endhighlight %}
