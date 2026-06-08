# matlab-lab-task



function e= Fact\_Nmbr(num)

e=1;



for i : a

&#x20;   e=e\*i;





end



end



function rev = Reverse\_Number(num)

rev=0;



while num>0

&#x20;   digit=rem(num,10);

&#x20;   rev=rev\*10+digit;

&#x20;   num=floor(num/10);



end

end



function table\_generator(num)

for i=1:10

&#x20;   disp(\[num2str(num)] 'x' num2str(i) '=' num2str(num\*i)]);





end



end



