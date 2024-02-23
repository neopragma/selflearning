function replace() {
    sed -i '.bak' -e "s/$1/$2/g" $(find . -type f)
    find . -name "*.bak" -type f -delete
}
