.filter-list{
    display:flex;
    flex-direction:column;
    gap:1rem;
}

.filter-list label{
    display:flex;
    align-items:center;
    gap:.75rem;
    cursor:pointer;
}

.filter-list span{
    font-size:.95rem;
    color:var(--color-text);
}

<!------->

.price-range__labels{
    display:flex;
    justify-content:space-between;
    margin-bottom:.8rem;
}

.price-range__slider{
    width:100%;
    margin-bottom:.75rem;
}

.price-range__values{
    display:flex;
    justify-content:space-between;
}

.price-range__labels,
.price-range__values{
    font-size:.9rem;
    color:var(--color-text);
}

.price-range__slider{
    width:100%;
    margin-bottom:.75rem;
    appearance:none;
    -webkit-appearance:none;
    height:6px;
    border-radius:999px;
    background:var(--color-border);
    cursor:pointer;
}

.price-range__slider::-webkit-slider-thumb{
    appearance:none;
    width:18px;
    height:18px;
    border-radius:50%;
    background:var(--color-primary);
    cursor:pointer;
    border:3px solid var(--color-white);
    box-shadow:var(--shadow-sm);
}

<!-------->
.filter-tags{
    display:flex;
    flex-direction:column;
    gap:1rem;
}

.filter-tag{
    width:100%;
    display:flex;
    align-items:center;
    gap:.85rem;
    padding:.9rem 1rem;
    border:1px solid var(--color-border);
    border-radius:var(--radius-md);
    background:var(--color-white);
    cursor:pointer;
    transition:var(--transition);
}

.filter-tag span:last-child{
    font-size:.95rem;
    font-weight:500;
    color:var(--color-black);
}

.filter-tag__color{
    width:14px;
    height:14px;
    border-radius:50%;
    flex-shrink:0;
}

.filter-tag__color--green{
    background:#3BB273;
}

.filter-tag__color--blue{
    background:#5B8DEF;
}

.filter-tag__color--orange{
    background:#F5A623;
}
