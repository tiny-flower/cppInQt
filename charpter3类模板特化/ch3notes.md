#chapter3类模板特化
##3.1类模板特化
```
template<typename T>
class stack {
    private:
        std::vector<T> elems;
    public:
        void push(T const&elem){
            elems.push_back(elem);
        }
        void pop(){
        if(elems.empty()) return;
        elem.pop_back();
        }
        T top() const{
        if(elems.empty()) return;
        return elems.back();
        }
}
```
