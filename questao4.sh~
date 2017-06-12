py=0
tot=0
txt=0
c=0
for file in $(ls .)
do
case "$file" in
    
    *.txt)
        txt=$(( $txt + 1 ))
        tot=$(( $tot + 1 ))
        ;;
    *.c)
        c=$(( $c + 1 )) 
        tot=$(( $tot + 1 ))
        ;;
    *.py)
        py=$(( $py + 1 ))
        tot=$(( $tot + 1 ))
        ;;
    
     *) 
        ;;
esac
done
echo "PY = $py"
echo "TXT = $txt"
echo "C = $c"
echo "Total = $tot"
